// C
switch (k) {
    case 1:
    case 2:
        j = 2 * k - 1;
        break;
    case 3:
    case 5:
        j = 3 * k + 1;
        break;
    case 4:
        j = 4 * k - 1;
        break;
    case 6:
    case 7:
    case 8:
        j = k - 2;
        break;
}

// Ruby
case k
when 1, 2
  j = 2 * k - 1
when 3, 5
  j = 3 * k + 1
when 4
  j = 4 * k - 1
when 6, 7, 8
  j = k - 2
end

// Erlang
case k of
    _ when k == 1; k == 2 -> J = 2 * K - 1;
    _ when k == 3; k == 5 -> J = 3 * K + 1;
    4 -> J = 4 * K - 1;
    _ when k >= 6, k <= 8 -> J = K - 2
end.

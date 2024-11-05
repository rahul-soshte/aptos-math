# Supported Integer Types in Move

Move supports six unsigned integer types: `u8`, `u16`, `u32`, `u64`, `u128`, and `u256`. Each type has a range from 0 up to its maximum value, as detailed below:

- **Unsigned 8-bit integer (`u8`)**
  - Range: 0 to 255 (two hundred fifty-five)

- **Unsigned 16-bit integer (`u16`)**
  - Range: 0 to 65,535 (sixty-five thousand five hundred thirty-five)

- **Unsigned 32-bit integer (`u32`)**
  - Range: 0 to 4,294,967,295 (four billion two hundred ninety-four million nine hundred sixty-seven thousand two hundred ninety-five)

- **Unsigned 64-bit integer (`u64`)**
  - Range: 0 to 18,446,744,073,709,551,615 (eighteen quintillion four hundred forty-six quadrillion seven hundred forty-four trillion seventy-three billion seven hundred nine million five hundred fifty-one thousand six hundred fifteen)

- **Unsigned 128-bit integer (`u128`)**
  - Range: 0 to 340,282,366,920,938,463,463,374,607,431,768,211,455 (three hundred forty undecillion two hundred eighty-two decillion three hundred sixty-six nonillion nine hundred twenty octillion nine hundred thirty-eight septillion four hundred sixty-three sextillion four hundred sixty-three quintillion three hundred seventy-four quadrillion six hundred seven trillion four hundred thirty-one billion seven hundred sixty-eight million two hundred eleven thousand four hundred fifty-five)

- **Unsigned 256-bit integer (`u256`)**
  - Range: 0 to 115,792,089,237,316,195,423,570,985,008,687,907,853,269,984,665,640,564,039,457,584,007,913,129,639,935 (one hundred fifteen quattuorvigintillion seven hundred ninety-two trevigintillion eighty-nine duovigintillion two hundred thirty-seven unvigintillion three hundred sixteen vigintillion one hundred ninety-five novemdecillion four hundred twenty-three octodecillion five hundred seventy septendecillion nine hundred eighty-five sexdecillion eight quadrillion six hundred eighty-seven trillion nine hundred seven billion eight hundred fifty-three million two hundred sixty-nine thousand nine hundred eighty-four quintillion six hundred sixty-five quadrillion six hundred forty trillion five hundred sixty-four billion thirty-nine million four hundred fifty-seven thousand five hundred eighty-four billion seven million nine hundred thirteen million one hundred twenty-nine thousand six hundred thirty-nine and nine hundred thirty-five)


# Observations

1. Move doesn't support signed integers like i64, i128, etc. You would have to build one entirely new module for it.
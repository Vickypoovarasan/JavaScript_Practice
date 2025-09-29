


    ==>     checkValidity() ===> returns true / false..

    ==>     reportValidity()    ==> show browser error popup..

    ==>     setCustomValidity("msg")    ==> set your own msg..

    ==>     validity    ==> object with sepicfic error flag..

    


    1. valueMissing.

            ==> Occurs it  field ha required but is empty..

    2. typeMismatch.

            ==> Occurs when input type doesn't match like (email, url)..

    3. patternMissmatch.

            ==> When value doesn't match regax in pattern attribute..

    4. tooShort / tooLong.

            ==> Check min-length and max-length

    5. rangeUnderflow / rangeOverflow

            ==> For number / date input outside min or max..

    6. stepMissmatch.

            ==> When value doesn't match step rule..

    7. badInput.

            ==> When browser can't convert input..

    8. customError.

            ==> If you used .setCustomValidity().
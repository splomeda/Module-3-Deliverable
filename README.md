# Module 3 Deliverable

GIT 337 Mod 3 Deliverable

A.I. Disclosure:

1. Asked Google Gemini what "Native control/type" is referring to.
2. Asked Gemini what "Sensitivity and minimization decision" means.
3. Asked Gemini how to word wrap a string of characters.
4. Asked Gemini how to fix error "Bad value for attribute action on element form: Must be non-empty" without inputing a link. Gemini said use a "." (period) instead of nothing.
5. Asked Gemini what the standard maximum character counts are for Name, Email, Address.
6. Needed help with the pattern attribute for telephone format. After seeing it, I understand how it works, i.e. for the first digit, it can be any number 0 through 9 [0-9] and there are 3 {3} digits before the first hyphen '-' and so on.
7. Asked Gemini how the browser passes along to the user, through assistive tech, that a field is required. Gemini says, "Browser natively flags the element as invalid to assistive tech and pauses form submission."
8. Asked Gemini how the browser alerts the user that an email address is invalid, "The browser flags the element as invalid to assistive tech, natively blocks form submission, and alerts the user to a broken entry structure."
9. Asked Gemini how to make the four-digit year in mm/dd/yyyy for the date limited to 4 digits. Answer: max="9999-12-31".
10. Asked Gemini how to add a red border around a field that the browser indicates is a required field.

    input[type="email"]:user-invalid {
    border: 2px solid #dc2626;
    background-color: #fef2f2;
    }

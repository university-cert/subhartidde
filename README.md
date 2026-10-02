# Subharti University - Degree Verification

## URL Format
```
https://university-cert.github.io/subhartidde/Degree.aspx?EN=Z1120613208
```

## How to Add New Student
Open `Degree.aspx` and find the `students` object in the `<script>` section.
Add a new line:
```js
"ENROLLMENT_NO": { degreeSerial: "DEGREE_SERIAL_NO" },
```

Then commit and push.

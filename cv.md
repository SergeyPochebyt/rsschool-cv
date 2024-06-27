# Pochebyt Sergey

### Contact:

##### tel. + 375(29)358-49-77

##### e-mail: sergeymailmobile@gmail.com

### Objective:

##### IT career development, web-design.

### Skills:

##### C#, JS, html, css.

### Code example:

    ```
    public static string GetPositiveHex(this int number)
        {
            if (number < 0)
            {
                throw new ArgumentException($"Incorrect {nameof(number)}");
            }

            char[] hexChar = new[] { '0', '1', '2', '3', '4', '5', '6', '7', '8', '9', 'A', 'B', 'C', 'D', 'E', 'F' };
            var remainder = number;
            string resultString = string.Empty;
            const int numericSystem = 16;
            while (remainder > 0)
            {
                var result = remainder % numericSystem;
                resultString = $"{hexChar[result]}{resultString}";
                remainder /= numericSystem;
            }

            return resultString;
        }
    ```

### Education:

##### Faculty of Radio Physics and Computer Technology of the Belarusian State University

### English:

##### Intermediate

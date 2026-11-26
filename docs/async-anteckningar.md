# Varför en falsk fetch

Then primära anledningar är att data som vi hämtar kanske inte finns tillgänglig just då man skriver koden. Server nere, man själv har strul med datorn eller kanske domänen är inte längre valid. Listan kan göras lång. Detta blir problematisk speciellt OM koden man skrivit är korrekt. Dessutom går det snabbare att utveckla(anropen görs lokalt) och man kan simulera olika server fel, finns fler än 404. Finns inga rate limit när man kör lokalt också :D

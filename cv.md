# Resume of Sergey Sudakov
 *Personal data:*
 1. Email: serg.fantasy@yandex.ru
 2. Phone: 89684585742
 3. Location: Moscow

  # About me
I'm self educating web programming developer. I'm interested in JS and want to be a professional web developer. i've got some commercial experience in development (https://melon.su/, https://goststeclo.ru/). This my profile in the kata codewars (https://www.codewars.com/users/sergjess). Every day I study something new in this sphere (articles in habr, youtube tutorials, telegram channels suach as 'Просто разработка', 'На фронте' etc).

    # Skills:

   1. Html - base level  
   2. CSS(SCSS) - base level
   3. JS - base level
   4. React JS-  base level
   5. Webpack - base level
   6. Gulp - base level  
   7. Git - base level  
   8. English -  B1

   # Code example:
   ```
    function humanReadable(seconds) {
    const secondsInMinutes = 60;
    const secondsInHours = 3600;
    let hoursResult = (seconds - (seconds % secondsInHours)) / secondsInHours;
    const withoutHours = (seconds % secondsInHours);
    let secondsResult = (withoutHours % secondsInMinutes);
    let minuteResult = (withoutHours - secondsResult) / secondsInMinutes;
    const hRes = (hoursResult < 10) ? '0' + hoursResult : hoursResult;
    const mRes = (minuteResult < 10) ? '0' + minuteResult : minuteResult;
    const sRes = (secondsResult < 10) ? '0' + secondsResult : secondsResult;
    return `${hRes}:${mRes}:${sRes}`;
}
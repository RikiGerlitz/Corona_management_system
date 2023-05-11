# Corona management system server 
# Riki Gerlitz

## אופן השימוש

הוספת אדם למערכת
```js
    http://localhost:4001/api/people
```
![alt text](./images/AddPersondetails.png);

שליפת פרטי אדם
```js
    http://localhost:4001/api/people/209275833
```
![alt text](./images/GetPersonDetails.png);

שליפת פרטי אדם בקורונה
```js
http://localhost:4001/api/people/personFullDetails/209275833
```
![alt text](./images/GetPersonAndCoronaDetails.png);

שליפת כל האנשים
```js
http://localhost:4001/api/people
```
![alt text](./images/GetAllPeopleDetails.png);

שליפת כל פרטי קורונה
```js
http://localhost:4001/api/corona
```
![alt text](./images/GetAllCoronaDetails.png);

שליפת פרטי קורונה לאדם
```js
http://localhost:4001/api/corona/209275833
```
![alt text](./images/GetCoronaDetailsById.png);

הוספת פרטי קורונה
```js
http://localhost:4001/api/corona/209275833
```
![alt text](./images/AddCoronaDetails.png);


בשביל להתקין צריך להריץ בשורת הפקודה

```js
npm install --save
```

הותקנו במערכת
```js
npm i mongoose
```

```js
npm i dotenv
```

```js
npm i "body-parser"
```

```js
npm i express  
```
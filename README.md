# Enviornmental Variable 
1. Create  a file at the root of the project
```
.env
```
2. Inside the .env file add the text:
- you must use `NEXT_PUBLIC` or else this will not work
```
NEXT_PUBLIC_TITLE = "Digital Design and Development"
```
On the page, in between the export and return write the variable:
```
var title = process.env.NEXT_PUBLIC_TITLE;
```
{title}
```
5.Make sure the `.gitignore` files has the `.env` inside
- you want to prevent the secret title to be shown

```
## BCIT Data from Digital Design and Development Diploma

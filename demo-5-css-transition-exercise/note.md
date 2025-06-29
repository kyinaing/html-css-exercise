```
.btn {
  border: 2px solid black;
  padding: 10px 20px;
  display: inline-block;
  margin-top: 30px;
  transition: background-color 5s;
  /* or */
  transition: color 3s, background-color 1s;
}

.btn:hover {
  background-color: orangered;
}
```


====================================================================
```
.btn {
  border: 2px solid black;
  color: orangered;
  padding: 10px 20px;
  display: inline-block;
  margin-top: 30px;
  background-color: white;
  transition: transform 3s ease-out;
}

.btn:hover {
  transform: translateX(100px);
}
```
===================================================================
```
.btn {
  border: 2px solid black;
  color: orangered;
  padding: 10px 20px;
  display: inline-block;
  margin-top: 30px;
  background-color: white;
  transition: background-color 2s ease-in, color 1s ease-out 2s;
}

.btn:hover {
  background-color: olive;
  color: magenta;
}
```
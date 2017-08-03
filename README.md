# ng4-tips

To kill processes still holding angular port:
```batch
netstat -ano | findstr :4200
taskkill /PID 4888 /F
```
# taskkill /PID <process id displayed at the end> /F

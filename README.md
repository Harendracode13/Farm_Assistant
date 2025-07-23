# Farm_Assistant
<br>
<b>both (receiver & sender): </b>  &nbsp; Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass <br>
	&nbsp;&nbsp;	.\de_env\Scripts\Activate.ps1 <br>
<b> 1 receiver: </b> &nbsp;	cd ./receiver <br>
		uvicorn main:app --reload --port 8001 <br>
2 sender: &nbsp;	cd ./sender <br>
	&nbsp;	uvicorn main:app --reload --port 8000 <br>
3 go to: &nbsp;	http://localhost:8001/.\de_env\Scripts\Activate.ps1

# Singleton-Pattern
The Best Way to implement singleton pattern is to  use this script and where evenr you want to access the script data wheter in same scene or in other scene just call the script instance.

How to use
public Class Someone : Singleton<Someone>
{
// Do Something
public int GetNumber()
{
return 5;
}
}

How to Access :

other Class
{
 Awake{
 Someone.Instance.Getnumber();
 }
}

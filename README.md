# FirebaseDatabase-Library-Csharp
A C# Library to easily manage you FirebaseDatabase

Initializing the FirebaseDatabase Object

using Bometh.FirebaseDatabase

FirebaseDatabase db = new FirebaseDatabase()
{
  link = "Firebase Database Link"
  authsecret = "Firebase Database Secret"
};

Seting Data

db.Set("path", data);

Updating Data

db.Update("path", data);

Getting Data

testObject result = db.Get<testObject>("path");
 
Deleting Data

db.Delete("path");
 

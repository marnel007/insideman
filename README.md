# insideman
uptimerobot.com InsideMAN {Running as an Service}

Allows you to use UptimeRobot inside you firewall.


BASEURL (The URL from UptimeRobot)
APIKEY  (For future use)
ServiceWaitSec   (For future use)
Enable (to do this check)
UPTIMETOKEN (Get this from UptimeRobot)
TYPE (1 Ping host)
TYPE (2 PORT CHECK)
TYPE (3  Website Check)
TYPE (4 Not used yet)
TYPE (5 Checks if EXE Running)
HOST (Host is IP based or Domain Based)
PORT (The port to check for {TYPE 2})
CHECKSEC (How man sec to check this)
EXEAPP (The EXE to Check {C:\test\test.exe})


*** One host can check 4 Diff Types ***

	"BASEURL": "https://uptime.",
	"APIKEY": "",
	"ServiceWaitSec": "15",
	"Check1": {
		"Enable": "True",
		"UPTIMETOKEN": "m787607448-d63da760299cd6625",
		"TYPE": "1",
		"HOST": "23.133.176.1",
		"PORT": "",
		"CHECKSEC": "45",
		"EXEAPP" : ""
	},
	"Check2": {
		"Enable": "True",
		"UPTIMETOKEN": "m787675854-085620c5381b107f1bb2",
		"TYPE": "2",
		"HOST": "23.133.176.40",
		"PORT": "3389",
		"CHECKSEC": "45",
		"EXEAPP" : ""
	},
	"Check3": {
		"Enable": "True",
		"UPTIMETOKEN": "m787681108-159f57fc230e5dc71a",
		"TYPE": "3",
		"HOST": "https://keystonesolutions.io/",
		"PORT": "",
		"CHECKSEC": "45",
		"EXEAPP" : ""
	},
	"Check4": {
		"Enable": "True",
		"UPTIMETOKEN": "m787607448-35354345435345",
		"TYPE": "5",
		"HOST": "",
		"PORT": "",
		"CHECKSEC": "45",
		"EXEAPP" : "c:\test\test.exe"
	},
	"Check5": {
		"Enable": "false",
		"UPTIMETOKEN": "m787607448-5345345345345345345",
		"TYPE": "4",
		"HOST": "",
		"PORT": "",
		"CHECKSEC": "45",
		"EXEAPP" : ""
	}
}

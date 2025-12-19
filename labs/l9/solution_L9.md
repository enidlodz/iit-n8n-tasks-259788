created with proper name
![alt text](l9_a_s1.png)

added code node with proper code
![alt text](l9_a_s3.png) 

response with HTML 200 OK in respond to webhook
![alt text](l9_a_s4.png) 

lecture event parsed correctly with `webhook-test` in browser
![alt text](l9_a_s5.png)

after publishing, `webhook` processes correctly (done here with `curl`)
![alt text](l9_a_s7.png)

---
created with proper name
![alt text](l9_b_s1.png)

GET from API w/ JSON
![alt text](l9_b_s3.png)

proper JSON response in respond to webhook
![alt text](l9_b_s4.png) 

API response in `webhook-test`
![alt text](l9_b_s5.png)

API response in published `webhook` (done with `curl`)
![alt text](l9_b_s6.png)

---

created with proper name
![alt text](l9_c_s1.png)

code in javascript node
![alt text](l9_c_s3.png)

write file node as defined in exercise MD file
![alt text](l9_c_s4.png)

respond to webhook node
![alt text](l9_c_s5.png)

no matter if the `data` folder is owned by `$(whoami)`, nor if it has `drwxrwxrwx+` permissions, the file refuses to write. i've tried `/workspaces/iit-n8n-tasks-259788/data/notes.txt`, `~/data/notes.txt`, some combination of the two, to no avail. i've genuinely ran out of ideas.
![alt text](l9_c_sError.png)
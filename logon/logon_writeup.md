Description
The factory is hiding things from all of its users. Can you login as Joe and find what they've been looking at? https://jupiter.challenges.picoctf.org/problem/44573/ (link) or http://jupiter.challenges.picoctf.org:44573


ok, so we need joe's credentials.. lets start with source code
2. password is not validated, so lets try Joe as username and any password....
3. Im in but no flag, lets look at the cookies, if i chane username to joe, remove password and changwe admin to true, what happens?
4. flag obtained. picoCTF{th3_c0nsp1r4cy_l1v3s_0c98aacc}

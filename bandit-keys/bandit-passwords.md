# Bandit Keys

1. Bandit level 1 password: 6y2kwnwK6grgvwvpvLaa2T1cpFEKOhNR

2. Bandit level 2 password: PK8fYLZg2hnHSz83plBL1iEPKdD3QToB

3. Bandit level 3 password: 7ZZ2LFrykP2zEyvBl4m3clcL7tGYJPME

4. Bandit level 4 password: xzTXq1rDJQVVAzdv5cHq1TQytTWufAMq

5. Bandit level 5 password: 6C7h9GD8M6ai5nr7wo1RonrzFjj9yIrG

6. Bandit level 6 password: pXa26xhMWaC2SvDotA4r9EgZkulOeSBW

7. Bandit level 7 password: Bmnnvf82KzQlfxgAI2d1zYbr1u9pr3E3

8. Bandit level 8 password: VR1ljMayciFxbnUokuQmJFw6QC9VKtub

9. Bandit level 9 password: EjmOSvuAu7sGAHqHVcBDPirRe9T03kxl

10. Bandit level 10 password: B0s2khmbT9u0geKuOoVGW3JZKhndE3BG

11. Bandit level 11 password: pYfOY6HwUsDj5rL9UvyhU7MCmv8vN5Ro

12. Bandit level 12 password: GROozWPO8QyN0mGrjUkID0WCYkZiQxrN

13. Bandit level 13 password: qQYQiHOBPR8zR61qxYqX45quvihF2uzk

14. Bandit level 14 password: Logged into the server as bandit13 and found the file "sshkey.private" in the home directory. Knowing the location of the file I can transfer it to my machine by using scp. Permission adjust to chmod 700 to get access to bandit14 by ssh -i sshkey.private bandit14@bandit.labs.overthewire.org -p 2220 we got into the server as bandit14.

15. Bandit level 15 password: pbLYuZtTg4MgaqfJx8jbA9gKKGqM68A7

16. Bandit level 16 password: kS0Hf0u5HiXFwKMKFqXvPdOTNGGa0X8V

17. Bandit level 17 password: For getting inside of bandit 17 I identify localhost ports with nmap after used openssl s_client to find out the right port. Once connected I past the bandit16 password. I had public key Create a file give chmod 600 permission connect with ssh -i. What I did is Port scanning, Service Discovery, SSH Key (RSA).

18. Bandit level 18 password: OQxXZjELndr90zuhOTDYBEomI0SZITXI

19. Bandit level 19 password: KpsOfPkcP7i1FlIExk2QEjyt6dw8dxZI

20. Bandit level 20 password: 4pIjcunZ0fK2vmp3IwfG8Vf7VhxD6pOA Takeaways: SUID(SetUID) Indicated by an "s" in file permissions. It grants the executor the temporary permissions of the file owner. This is critical for system security.Effective UID: The identity the OS uses for permission checks, distinct from the real user ID.

21. Bandit level 21 password: bW9kBv5WC3P4yoDyf12LSdGuNz5ka6hY Takeaways: Job control (&): It allows running commands in the background, freeing up the terminal from other tasks. Reverse Connection: Instead of attacking a target directly, we force the target to connect back to us (Similar to reverse shell concepts)

22. Bandit level 22 password: RYVux2rHEm9tiXHmLFzuR7Vhx6AZQMEz Takeaways: Cron / Crontab: Linux's scheduled task mechanism. It is a must for system administration for tasks like backups. Tracing Execution: Starting from a clue (cron file), finding the executed script, and reading it's code to understand it's behaviour. Fundamental skill in security.

23. Bandit level 23 password: gKXDTAXnIz3OBxiPjRZ2uqutUlPZrBsw

24. Bandit level 24 password: hVQMk3lJNsmQ7VF3ubyrNNBom7BOgVXv

25. Bandit level 25 password: SoHfqMOEqIX2IYKVciZxvgpR9a2Djx4P

26. Bandit level 26 password: jHdv2ELQhT22BkprMNDjybZDAkw1zeBJ

27. Bandit level 27 password: STJLJBRRphMxKB392CT4iOr5CbzPU9ER

28. Bandit level 28 password: y8Yd2ssKcpHpud7UvOSOxwamRMzIGIeQ

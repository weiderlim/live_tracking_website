# Guides 

Full idea : https://www.geeksforgeeks.org/how-to-deploy-flask-app-on-aws-ec2-instance/

Corey Tutorials : https://www.youtube.com/watch?v=LUFn-QVcmB8&list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH&index=14

Registering Domain name in AWS ecosystem : https://medium.com/@yashpatel007/how-to-connect-your-amazon-ec2-instance-with-a-domain-name-80ad8959078

SSL : https://certbot.eff.org/instructions?ws=nginx&os=ubuntubionic
https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-20-04


# General steps to host own website : 
1. Create server instance (AWS EC2 in this case)
2. Create Elastic IP address (so that IP address is fixed)
3. Get domain name (from domain name provider websites). There is a limit on the number of years the domain is owned, need to renew. 
4. Create SSL for HTTPS network connection - Certbot
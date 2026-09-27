# Whatsapp | OSINT

We can get IP address of a whatsapp caller by analysing the traffic in wireshark

## Finding IP address of a WhatsApp caller (Only works if call is picked up)

{% stepper %}
{% step %}
### Install Wireshark on PC
{% endstep %}

{% step %}
### Check your ip address of PC

![](<.gitbook/assets/image (191)>)
{% endstep %}

{% step %}
### Start Wireshark and apply the following filter

```
ip.addr == 192.168.18.13 && udp
```
{% endstep %}

{% step %}
### Now make the call and look for our IP.

![](<.gitbook/assets/image (193)>)
{% endstep %}

{% step %}
### We can check the IP location

![](<.gitbook/assets/image (194)>)
{% endstep %}
{% endstepper %}

If you see something like this than the actual IP is where the STUN request was made.

![](<.gitbook/assets/image (196)>)

#### Best OSINT Course for Beginners

[![Logo](https://osint.cavementech.com/~gitbook/image?url=https%3A%2F%2Fwww.udemy.com%2Ffrontends-course-landing-page%2Ffavicon.ico\&width=20\&dpr=3\&quality=100\&sign=a456e6ab72ed4d0430b74f6f96aca94c\&sv=3)Practical OSINT: The Complete Course for BeginnersUdemy](https://www.udemy.com/course/practical-osint/?referralCode=0848C4EC66BBAC2534D6)

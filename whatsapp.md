# whatsapp

We can get IP address of a whatsapp caller by analysing the traffic in wireshark

### Finding IP address of a WhatsApp caller (Only works if call is picked up)

{% stepper %}
{% step %}
## Install Wireshark on PC
{% endstep %}

{% step %}
## Check your ip address of PC

<figure><img src=".gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
## Start Wireshark and apply the following filter

```
ip.addr == 192.168.18.13 && udp
```
{% endstep %}

{% step %}
## Now make the call and look for our IP.

<figure><img src=".gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
## We can check the IP location

<figure><img src=".gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

If you see something like this than the actual IP is where the STUN request was made.

<figure><img src=".gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

#### Best OSINT Course for Beginners

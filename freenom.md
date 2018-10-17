# Free public hostname through freenom.com

Freenom.com is an example of a free DNS provider. Below is a brief description on how to setup a new domain and redirect it to a public IP. 

## Regsiter Domain

1. Browse to [freenom.com](https://freenom.com)
1. Sign in
1. Go to *Services > Register a New Domain*
1. Find available domain name 
1. Select *Get it Now!*
1. Select *Checkout*
1. Select desired allocation Period
1. Select *Continue*
1. Fill in your details and *Complete Order*

## Update DNS record

1. Browse to [freenom.com](https://freenom.com)
1. Sign in
1. Go to *Services > My Domains*<br /> ![Services > My Domains](\img\freenom-my-domains-menu.png)
1. Select *Manage Domain* to configrue a specific domain<br /> ![Manage Domain](\img\freenom-manage-domains-menu.png)
1. Select *Manage Freenom DNS* to access DNS configuration
<br /> ![Manage Freenom DNS](\img\freenom-manage-freenom-dns-menu.png)
1. Add an A record that point to your server public external IP 
<br /> ![DNS A record](\img\freenom-dns-a-record.png)
1. Save Changes. Note, it may take a short while before new redirect has been propagated on Internet. 


# Evilgins3-infra-tips-and-setup-guide

# phishing-HTML-linter.py - 
This script will help you identify issues with your HTML code that you wish to use as your Phishing template.

It looks for things such as:

Embedded Images
Images without ALT
Masqueraded Links
Use of underline tag <u>
HTML code in <a> link tags
<a href="..."> URL contained GET parameter
<a href="..."> URL contained GET parameter with URL
<a href="..."> URL pointed to an executable file
Mail message contained suspicious words
Mail message contained unsupported HTML tags
Mail message contained unsupported HTML attributes
Such characteristics are known bad smells that will let your e-mail blocked.

# install_evilginx3.sh

The install_evilginx3.sh script automates the setup of the Evilginx3 adversary-in-the-middle (AiTM) phishing framework. Typically designed for Ubuntu Linux environments, the script fetches Go, resolves dependencies, and configures the permissions required to bind the proxy to privileged ports.


# DancingRightToLeft.py - A script abusing Right-To-Left Override unicode byte to rename phishing payloads.

PS> py DancingRightToLeft.py 502.html fax

    :: Dancing Right-To-Left

    A script abusing Right-To-Left Override unicode byte to rename phishing payloads.

    Mariusz Banach / mgeeky '22, (@mariuszbit)
    <mb@binary-offensive.com>

INPUT:

    Payload Filename                                 :  502.html
    Payload Extension                                :  ".html"
    Decoy payloads' extension as                     :  ".fax"

OUTPUT:

    Your file was named in following way             :  "502 \u202exaf.html"

    Your filename will look like this (simulated)    :  "502 lmth.fax"
    Your filename will look like this (real display) :  502                                              lmth.fax

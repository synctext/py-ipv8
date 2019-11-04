IPv8 Documentation
==================

Welcome to the IPv8 documentation! This file will help you navigate the existing documentation.
The documentation will explain the concepts behind IPv8, the architecture, and guide you to making your first overlay.

IPv8 Features
==================

The IPv8 overlay offers an encrypted network connection to a known person which is robust against various network problems and security issues. IPv8 is a networking layer which offers identities and exposes reputation functions, storage of reputation data, and calculates reputation levels. IPv8 is a mechanism designed to build trust. 

It offers public-key based identities and offers protection against eavesdropping, man-in-the-middle attacks, peer failure, network failure, packet loss, change of IP numbers, network mobility, and blocking by NAT/Firewalls. IPv8 offers global connectivity through integrated UDP NAT puncturing, announcement of your identity claim and a web-of-trust. IPv8 has an integrated attestation service. You can use IPv8 for official verification that something is true or authentic, according to a trustworthy attestor. By using zero-knowledge proofs we attempt to minimize privacy leakage.

Why does IPv8 exist?
==================

Problems with the very fabric of The Internet, IPv4, are mounting. The approach of IPv6, Mobile IP, and IPSec is hampered by fundamental architectural problems. One solution is moving the intelligence up to a higher layer in the protocol stack and towards the end points. Our end-points are not dependant only any central infrastructure. Our architecture is academically pure and fully decentralised; to the point of obsession. IPv8 is based on the principle of self-governance. Like Bitcoin and Bittorrent our IPv8 overlay is permissionless and requires no maintenance. 

IPv8 aims to help restore the original Internet; for free; owned by nobody; for everyone. By design IPv8 does not need any committee of oversight, no monthly payment to any essential infrastructure provider and lack any central identity registration service provider. 


Table of contents
=================

.. toctree::
   :maxdepth: 2
   :caption: Preliminaries:

   preliminaries/install_libsodium.rst

.. toctree::
   :maxdepth: 2
   :caption: Basics:

   basics/overlay_tutorial.rst
   basics/crawler_service_tutorial.rst
   basics/attestation_tutorial.rst

.. toctree::
   :maxdepth: 2
   :caption: Further reading:

   further-reading/trustchain.rst
   further-reading/anonymization.rst


Search
======

* :ref:`genindex`
* :ref:`search`


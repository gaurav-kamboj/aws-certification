
# AWS Route53 FAQs

[https://aws.amazon.com/route53/faqs/](https://aws.amazon.com/route53/faqs/)

DNS servers translate requests for names into IP addresses, controlling which server an end user will reach when they type a domain name into their web browser. These requests are called "**queries**."

 - Each Route 53 account is limited to a **maximum of 500 hosted zones and 10,000 resource record sets per hosted zone**. 
 - Route 53 supports **wildcard entries** (a wildcard DNS record such as *.example.com will match queries for www.example.com and subdomain.example.com)
 - **Route 53 does not have a default TTL for any record type**. You must always specify a TTL for each record so that caching DNS resolvers can cache your DNS records to the length of time specified through the TTL.

**Does Amazon Route 53 use an anycast network?**

Yes. Anycast is a networking and routing technology that helps your end users’ DNS queries get answered from the optimal Route 53 location given network conditions. As a result, your users get high availability and improved performance with Route 53.

**DNS records supported by Route 53:**

1. A (address record)
1. AAAA (IPv6 address record)
1. CNAME (canonical name record)
1. MX (mail exchange record)
1. NAPTR (name authority pointer record)
1. NS (name server record)
1. PTR (pointer record)
1. SOA (start of authority record)
1. SPF (sender policy framework)
1. SRV (service locator)
1. TXT (text record)
1. Alias (an Amazon Route 53-specific virtual record)



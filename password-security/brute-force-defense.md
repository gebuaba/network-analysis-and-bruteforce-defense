# Password Security & Brute Force Defense

## Objective
Demonstrate how weak passwords can be compromised and how defensive controls
reduce brute-force effectiveness.

## Tools Used
- Hydra
- Burp Suite
- SSH
- PAM (pwquality, faillock)

## Attack Simulation
- Captured login requests using Burp Suite
- Performed brute-force attempts using Hydra
- Successfully accessed a vulnerable web application

## Defensive Controls Implemented
- Strong password policy (minimum length, complexity)
- Account lockout after repeated failures
- SSH service hardening

## Results
- Brute-force attempts failed after policy enforcement
- Lockout mechanisms worked during real login attempts
- Demonstrated difference between automated tools and real-world controls

## Security Takeaway
Strong authentication policies significantly reduce attack success and improve
overall system security.

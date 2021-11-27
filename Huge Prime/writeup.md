# Huge Prime

| Info | Value |
| :--- | :-----: |
| Categories | #Web |
| Score | 50 |
| Total Solve (Rate) | Unknown |

## Description

Find two numbers that multiply to be equal to this number which is the product of two primes: 22952152323332505688670761214671498225451684330137990990356473040741684014997701799009910066964917896400501477

## Attachments

Huge-Primes.zip
(Remarks: The .zip file was a website originally)

## Writeup

Upon Google, we found a tool called [Yafu](https://sourceforge.net/projects/yafu/), which can helps us to factor the semiprime number.

Using Yafu by entering the command `factor(22952152323332505688670761214671498225451684330137990990356473040741684014997701799009910066964917896400501477)`, we got our factors(63145347 and 3496275968) after short period of time!

Entering the factors into the website and we got our flag.

## Flag
`flag{984ur9q83ndj934jd}`
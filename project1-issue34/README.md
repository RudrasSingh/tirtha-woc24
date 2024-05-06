# Project Tirtha - Winter of Code 2024

## Brief Description

- This contribution stemmed from Winter of Code 2024, where I focused on Project Tritha. My role involved integrating Sign in with Google, a popular authentication method that adds a Google-managed button and corresponding scripts to the Tirtha website. While this simplifies user onboarding by leveraging existing Google accounts, it also introduces third-party logging. However, supporting popular IdPs like Google is essential for a seamless user experience. Therefore, we must strike a balance between offering convenient login options and minimizing the extent of external logging.

## Issue & Pull Request

- [Link to Issue](https://github.com/smlab-niser/tirtha-public/issues/34)
- [Link to Pull Request](https://github.com/smlab-niser/tirtha-public/pull/44)

## Changes Made

- The coding phase necessitated modifications to the core Python file previously responsible for Sign in with Google. To achieve this, I implemented Authlib's OAuth provider for user authentication and subsequent data storage within the session. Additionally, a new button facilitating sign-in through the chosen authentication method was strategically incorporated into the homepage's contribution section, enhancing user accessibility.

## Challenges Faced

- The initial challenge revolved around identifying a suitable alternative to Sign in with Google. Despite extensive web searches, the scarcity of options became apparent, likely due to Google's dominance and user-friendliness in the authentication space. Unfortunately, the limited alternatives I encountered also exhibited excessive tracking behavior. Through collaborative efforts with my mentor and by exploring resources on YouTube, we ultimately identified Authlib for Django as the optimal solution, effectively balancing user convenience with minimized external logging.

## My Socials

- [Github](https://github.com/RudrasSingh)
- [LinkedIn](https://www.linkedin.com/in/atulsinghc)
- [Twitter](https://twitter.com/atul_singh001)

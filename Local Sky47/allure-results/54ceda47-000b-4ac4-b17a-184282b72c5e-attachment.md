# Page snapshot

```yaml
- generic [active] [ref=e1]:
  - region "Notifications alt+T"
  - generic [ref=e3]:
    - img "Sky-47 logo" [ref=e5]
    - generic [ref=e8]:
      - heading "Create Account" [level=2] [ref=e9]
      - generic [ref=e10]:
        - textbox "Full Name" [ref=e13]: Daniyal
        - textbox "Email Address" [ref=e16]: user_1762949146244@yopmail.com
        - generic [ref=e18]:
          - textbox "Password" [ref=e19]: StrongP@ssw0rd!
          - button "Show password" [ref=e20] [cursor=pointer]:
            - img
        - generic [ref=e22]:
          - textbox "Confirm Password" [ref=e23]: StrongP@ssw0rd!
          - button "Show password" [ref=e24] [cursor=pointer]:
            - img
        - button "Create Account" [ref=e25] [cursor=pointer]
      - generic [ref=e26]:
        - generic [ref=e32]: OR
        - generic [ref=e33]:
          - link "Continue with Google" [ref=e34] [cursor=pointer]:
            - /url: https://fgcc0s0oso4oswgs44cc80wo.49.13.228.64.sslip.io/auth/google
            - img "google-icon" [ref=e35] [cursor=pointer]
          - button "Continue with GitHub" [ref=e36] [cursor=pointer]:
            - link "github-icon" [ref=e37] [cursor=pointer]:
              - /url: https://fgcc0s0oso4oswgs44cc80wo.49.13.228.64.sslip.io/auth/github
              - img "github-icon" [ref=e38] [cursor=pointer]
      - paragraph [ref=e40]:
        - text: Already have an Account?
        - link "Log In" [ref=e41] [cursor=pointer]:
          - /url: /login
  - alert [ref=e42]
```
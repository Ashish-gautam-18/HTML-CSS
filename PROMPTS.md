# Mistvale Tea Co. — AI Prompt Log Workflow

## Prompt 1
- Tool: ChatGPT (GPT-4o)
- Type: code
- Prompt:
  > Act as a senior frontend developer. Create a clean CSS Custom Property design system using these exact hex colors: Tea green (#1f3d2b), Leaf (#4f7942), Cream (#f6f1e7), Parchment (#ebe2cf), Saffron (#d9962b), Ink (#1b1b1b), and Error (#b3261e). Set up a responsive structure that forces a 2-column card grid on mobile phones and a single font loading link for Fraunces and Inter with display=swap.
- Outcome: accepted
- Why: It perfectly initialized the structural color layout tokens according to the strict guidelines and fixed the mobile layout constraint without any extra frameworks.

## Prompt 2
- Tool: Claude 3.5 Sonnet
- Type: code
- Prompt:
  > Write pure native Vanilla JavaScript to manage the checkout cart backend rules for an online store. We have an array called PRODUCTS. Enforce a maximum quantity cap of 5 packs per product, validate a coupon code 'WELCOME10' that gives 10% off on non-gift items only when the cart subtotal is at least ₹399, cap the maximum discount at ₹150, and charge ₹49 shipping unless the final net amount reaches ₹499. Do not use jQuery.
- Outcome: modified
- Why: The AI successfully generated the mathematical business rules, but it added escape backslashes (\$) to the template strings which broke the script in the browser. I manually refactored it to standard browser string concatenation.

## Prompt 3
- Tool: ChatGPT (GPT-4o)
- Type: code
- Prompt:
  > Write a non-blocking UI handler for a pincode delivery checker that uses a delayed asynchronous callback function named API.checkPincode(pin, callback). Ensure that when the user clicks 'Check', the text changes to 'Checking…' and the button is disabled to prevent multiple submissions, and re-enables properly once the callback completes.
- Outcome: accepted
- Why: It successfully handled the loader status and stopped double-click bugs while waiting for the simulated backend data response.

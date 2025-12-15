# QA Breakdown – Solana Wallet UI

🧪 Tested: Phantom wallet integration on a React DApp

- Route `/connect-wallet` fails silently if Phantom is not installed → added fallback modal  
- Asset `phantom-icon.svg` was missing in dark mode → fixed with conditional theme loader  
- RPC call `getBalance()` failed on slow networks → added loading spinner + retry logic  
- Deep link `/wallet?tab=transactions` broke on mobile → fixed with responsive tab logic

📦 Outcome: Delivered QA report + patch PR + onboarding guide for junior devs.

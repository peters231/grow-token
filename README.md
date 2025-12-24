# grow-token
$GROW: Redeemable company-backed token for Growing Enterprise Limited. Full treasury control, TON blockchain deployment, and controlled redemption logic.
grow-token/
├── contracts/                  # Smart contract files
│   ├── GROW.fif                # FunC contract file (TON) OR .sol for EVM
│   ├── GROW_testnet.fif        # Testnet version
├── scripts/                    # Deployment & testing scripts
│   ├── deploy.js                # Deployment script to TON
│   ├── test.js                  # Automated test scripts
├── ledger/                     # Optional: ledger integration instructions
│   └── README.md               # How to track tokens in Notion / Airtable
├── README.md                   # Project overview, setup instructions, workflow
├── LICENSE                     # MIT or your preferred license
├── .gitignore                  # Standard ignores
└── docs/                       # Optional: detailed diagrams, flowcharts
    └── redemption_flow.png

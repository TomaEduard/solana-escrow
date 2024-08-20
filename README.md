# solana-escrow
==> Searching for similarly named casks...
==> Casks
git-credential-manager

Download and Install the Solana CLI:  
<code>sh -c "$(curl -sSfL https://release.solana.com/v1.18.8/install)"</code>
<code>npm add @solana-developers/helpers</code>

Add Solana CLI to PATH: Add the following line to your .zshrc file to ensure the Solana CLI is in your PATH:  
<code>export PATH="$HOME/.local/share/solana/install/active_release/bin:$PATH"</code>

Apply the Changes:  
<code>source ~/.zshrc</code>

Verify the Installation:  
<code>solana --version</code>


This should install the Solana CLI and make the solana-install command available.

https://explorer.solana.com/

To install git-credential-manager, run:
brew install --cask git-credential-manager

<code>anchor test --skip-local-validation</code>

location: /escrow
<code>solana-keygen pubkey ./target/deploy/escrow-keypair.json</code>


----
<code>cargo clean</code>
<code>anchor build</code>

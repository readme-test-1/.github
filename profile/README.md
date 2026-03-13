<p align="center">
  <img src="https://raw.githubusercontent.com/readme-test-1/.github/main/assets/aave-logo.png" alt="Aave DAO" width="600">
</p>

<h1 align="center">Aave DAO</h1>

<p align="center">Official repositories of the Aave DAO</p>

---

<table>
<thead>
  <tr>
    <th width="220">Repository</th>
    <th width="480">Description</th>
    <th width="130">Created by</th>
    <th width="220">Maintained by</th>
  </tr>
</thead>
<tbody>
  <tr><td colspan="4"><h3>Core Protocol</h3></td></tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-v3-origin">aave-v3-origin</a></td>
    <td>The canonical Aave V3 codebase (v3.1 through v3.6). Foundry-based, formally verified, and the source of truth for all production pool deployments across 12+ networks.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr><td colspan="4"><h3>GHO</h3></td></tr>
  <tr>
    <td><a href="https://github.com/aave-dao/gho-origin">gho-origin</a></td>
    <td>Smart contracts for GHO - the DAO-native stablecoin minted directly against Aave collateral. Includes facilitator framework, discount rate logic for stkAAVE holders, and GSM (GHO Stability Module).</td>
    <td><a href="https://github.com/aave-labs">Aave Labs</a></td>
    <td><a href="https://github.com/aave-labs">Aave Labs</a>, <a href="https://github.com/TokenLogic-com-au">TokenLogic</a>, <a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/GhoDirectMinter">GhoDirectMinter</a></td>
    <td>A GHO facilitator contract that injects GHO liquidity directly into Aave pools, enabling GHO listing on non-Ethereum instances (e.g., Lido) without external market dependency.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr><td colspan="4"><h3>Governance</h3></td></tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-governance-v3">aave-governance-v3</a></td>
    <td>Aave Governance V3 smart contracts. Multi-chain proposal creation, voting via Ethereum storage proofs, and execution - enabling token holders to vote on L2s while keeping final settlement on Ethereum.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-delivery-infrastructure">aave-delivery-infrastructure</a></td>
    <td>a.DI (Aave Delivery Infrastructure) - the cross-chain messaging layer that connects governance on Ethereum to protocol instances on every network. Abstracts over multiple bridge providers (CCIP, Hyperlane, LayerZero, etc.) for redundancy.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/adi-deploy">adi-deploy</a></td>
    <td>Deployment scripts, payload templates, and maintenance tooling for a.DI. Used to onboard new networks, update bridge adapters, and manage CrossChainController upgrades across all Aave deployments.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-proposals-v3">aave-proposals-v3</a></td>
    <td>The monorepo where every Aave governance proposal is built, tested, and submitted. Contains Solidity payloads, fork-tested with snapshot diffs, plus a CLI generator to scaffold new proposals. The single entry point for all protocol changes.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-proposals-reports">aave-proposals-reports</a></td>
    <td>Public registry of security reviews for every Aave governance proposal before it goes to vote. The last line of defense ensuring proposal payloads do exactly what they claim - nothing more, nothing less.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr><td colspan="4"><h3>Umbrella</h3></td></tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-umbrella">aave-umbrella</a></td>
    <td>Aave Umbrella - the upgraded Safety Module. A staking-and-slashing system that semi-automatically covers reserve deficits using wrapped aTokens (waTokens). Replaces the legacy stkAAVE model with per-asset coverage pools and multi-reward distribution.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-umbrella-ui">aave-umbrella-ui</a></td>
    <td>DAO-owned frontend for Aave Umbrella. Stake, unstake, claim rewards, and monitor positions across networks - all without depending on third-party interfaces.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr><td colspan="4"><h3>Tooling</h3></td></tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-helpers">aave-helpers</a></td>
    <td>Foundry testing library for Aave protocol development. Provides governance proposal simulation, pool config snapshots, e2e testing suites, and proxy inspection utilities. The base layer every proposal author and service provider builds on.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-address-book">aave-address-book</a></td>
    <td>Single source of truth for every deployed Aave contract address across all networks. Import in Solidity or TypeScript - no more hardcoded addresses, no more stale configs. Auto-generated from on-chain registries.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-permissions-book">aave-permissions-book</a></td>
    <td>Transparency tool mapping every permission, role, and admin key across the entire Aave smart contract ecosystem. Shows who can upgrade what, which multisigs control which functions, and where trust boundaries lie - per pool, per network.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-price-feeds">aave-price-feeds</a></td>
    <td>Custom oracle adapters for Aave, including CAPO (Correlated Assets Price Oracle) for LSTs and yield-bearing tokens. Ensures price feeds respect growth caps and can't be manipulated through donation attacks or exchange rate jumps.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-v3-risk-stewards">aave-v3-risk-stewards</a></td>
    <td>Smart contracts that let risk service providers adjust Aave V3 parameters (caps, rates, LTV, liquidation thresholds) without full governance votes - but within strict on-chain bounds. Reduces governance overhead while keeping risk management agile.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-risk-stewards">aave-risk-stewards</a></td>
    <td>Operational repo for risk providers to execute Risk Steward updates. Foundry scripts, config snapshot diffs, and Safe transaction forwarding - the workflow layer on top of the Risk Steward smart contracts.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/seatbelt-gov-v3">seatbelt-gov-v3</a></td>
    <td>Automated governance simulation engine. Forks mainnet, executes proposals, and generates human-readable reports showing every state change, event, and potential issue - before a single vote is cast.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
  <tr><td colspan="4"><h3>Resources</h3></td></tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-brand-kit">aave-brand-kit</a></td>
    <td>Official Aave brand assets - logos, color palette, typography, and usage guidelines. The canonical source for consistent Aave visual identity across all integrations and communications.</td>
    <td><a href="https://github.com/aave-labs">Aave Labs</a></td>
    <td><a href="https://github.com/aave-labs">Aave Labs</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/bored-guides">bored-guides</a></td>
    <td>Operational documentation for Aave ecosystem workflows. Step-by-step guides covering technical procedures that keep the protocol running - from deployment processes to maintenance routines.</td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
    <td><a href="https://github.com/bgd-labs">BGD Labs</a></td>
  </tr>
</tbody>
</table>

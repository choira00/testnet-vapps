# vApp Submission: SocialSphere

## Verification
```yaml
github_username: "choira00"
discord_id: "956204700196282378"
timestamp: "2025-08-29"
```

## Developer
- **Name**: kamrul
- **GitHub**: @choira00
- **Discord**: choira#7272
- **Experience**: Background in web3 social apps, React + Node.js developer, interested in decentralized identity and communication.

## Project

### Name & Category
- **Project**: SocialSphere
- **Category**: social

### Description
SocialSphere is a decentralized social platform where users can connect, share content, and build communities without centralized control. It solves the problems of censorship, data privacy, and ownership by enabling users to control their social graph and content directly on-chain.

### SL Integration  
Use Soundness Layer (SL) for decentralized identity verification and reputation tracking.

Leverage SL’s zk-proofs to ensure privacy while maintaining trust between users.

Integrate SL to handle sybil resistance (preventing fake/multiple identities).
## Technical

### Architecture
Users register with SL identity.

Posts, comments, and likes are stored on decentralized storage.

Reputation and trust scores validated via SL.

A lightweight backend indexes and caches data for faster feed rendering.

### Stack
- **Frontend**: React + TailwindCSS
- **Backend**: Node.js/Express 
- **Blockchain**: Soundness Layer (primary), Ethereum/Polygon (optional for extra features)
- **Storage**: WALRUS/IPFS for content

### Features

Decentralized identity-based login with SL

User feed (posts, likes, comments)

Reputation & trust scoring system

Community groups & private messaging (future MVP)

## Timeline

### PoC (2-4 weeks)
- [ ]  Basic social feed (post, like)
- [ ] SL-based identity login
- [ ] Minimal UI with React

### MVP (4-8 weeks)  
- [ ] Full feed with comments & profiles
- [ ] SL reputation integration
- [ ] User testing & feedback loop

## Innovation
Unlike existing social platforms, SocialSphere is user-owned and censorship-resistant, with identity and trust anchored in SL. This ensures real users, fair reputation, and privacy-preserving interactions.

## Contact
choira#7272


**Checklist before submitting:**
- [ ] All fields completed
- [ ] GitHub username matches PR author  
- [ ] SL integration explained
- [ ] Timeline is realistic

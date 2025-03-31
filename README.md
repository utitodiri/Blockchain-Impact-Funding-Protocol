;; The-Blockchain-Impact-Flow: Decentralized Milestone-Based Funding Protocol
;; A transparent, secure mechanism for goal-oriented resource allocation

;; Core system configuration and error constants
(define-constant PROTOCOL_ADMIN tx-sender)
(define-constant ERR_PERMISSION_DENIED (err u300))
(define-constant ERR_RESOURCE_UNAVAILABLE (err u301))
(define-constant ERR_INVALID_PARAMETERS (err u302))
(define-constant ERR_TRANSACTION_FAILED (err u303))
(define-constant ERR_STATE_CONSTRAINT (err u304))

;; Temporal and operational parameters
(define-constant ESCROW_TIMEOUT u1008) ;;
(define-constant MAX_MILESTONE_RECIPIENTS u5)
(define-constant CHALLENGE_RESOLUTION_WINDOW u1008) 
(define-constant RATE_LIMIT_INTERVAL u144)
(define-constant MAX_DONATIONS_PER_INTERVAL u5)

;; Cryptographic and economic security parameters
(define-constant CHALLENGE_ECONOMIC_STAKE u1000000)


## ESB-01 Redundant if conditions
    remains

## ESB-02 Unlocked compiler version
    set to fixed 0.7.0

## ESB-03 Improper usage of and external type
    public can be used in contract call, remians the same

## ESB-04 Missing error messages
    add error messages

## ESC-01 Centralization risk in bridge.sol
    owners and operators are multisig wallet.

## ESC-02 Unknow cross-chain token transfer implementation
    remains

## ESC-03 Cross chain transaction atomicity
    remains

## ESC-04 User balance not recorded
    remains

## ESC-05 Centralized risk in functions transferNative and transferToken
    owners are multisig wallet.

## ESC-06 Variables that could be declared as constant
    fixed

## ESC-07 Redundant code components
    remains

## ESC-08 Missing emit events
    remains

## ESC-09 Variables that could be declared as immutable
    fixed

## ESC-10 Configuration variables may not be set up after contract deployment
    set the initial value of pause to be true

## ESC-11 Logic issue for cross-chain platform token transfer
    remains

## ESC-12 Lack of reasonable boundary
    no boundary
    Fee can be seen at frontend page, it's up to the user to deposit or not.

## ESK-01 Unknown usage of the MultisigWallt contract
    It was used to be owner and operator with different deployed controled by different members.
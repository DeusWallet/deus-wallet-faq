# 스왑 전 별도의 승인거래가 필요한 이유는 무엇인가요?

다음과 같은 스왑 거래에 참여하기 전:

- ERC20을 ETH로 변환
- ERC20을 다른 ERC20으로 교환
- BEP20을 BNB로 교환
- BEP20 토큰 교환

사용자는 별도의 승인 거래를 수행해야 합니다. 이러한 승인 거래는 일반적으로 경제적이며 DEX가 거래 실행을 위해 지정된 수량의 ERC20/BEP20 토큰을 공제하는 데 대한 사용자의 동의를 의미합니다.

승인 거래 중에 사용자는 DEX가 공제할 수 있는 토큰 금액을 지정할 수 있습니다. 또한 사용자는 향후 거래를 예상하여 더 많은 금액을 승인할 수 있으므로 후속 승인 거래가 필요하지 않습니다.

거래에 충분한 토큰 금액을 승인하지 않으면 거래가 실패하게 됩니다.
● Tests are important while creating smart contracts because they are immutable once they are deployed onto the blockchain. They give us a brief idea of the behavior we can expect once deployed. An assertion library called chai is used in this along with a testing framework called mocha for javascript that comes bundled with truffle.
This project creates and uses several tests in the TokenFarm.test.js file, some of which are listed below.

● The first test is to check if the three smart contracts have been deployed properly.

● The second test is to ensure that the required number of tokens have been transferred to the investor’s account from the person who has deployed it.

● The third test ensures that the investor Mock DAI wallet balance is correct before staking.

● The fourth test ensures that the investor’s staking status is true.

● There is one test that ensures that the DAPP tokens issued are equal to the DAI tokens staked by the investor

● Another test ensures that the issueTokens function, if called by anyone other than the owner is rejected.


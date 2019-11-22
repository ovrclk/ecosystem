<p align="center">
<img width="200" src="../../doc/founder3@2x.png">
</p>

**Challenge**: Become a Akash Provider

**Reward**: 2000 AKTs

**Instructions**:

1. Sign up for an Akash Account [Testnet](https://akash.network/testnet).
2. Follow the [Instructions](https://docs.akash.network/providers/kube) to become a Akash Provider.

**Submission**:

1. Fork the [ecosystem repository](https://github.com/ovrclk/ecosystem).
2. Clone the ecosystem repository to your workstation. For example, where `<user>` is your GitHub username:

```shell
git clone https://github.com/<user>/ecosystem.git
```

3. Create a file a file at `founders/level3/${MACHINE_ZONE}.yaml` with the below contents:

- Your participation id from [Akash Rewards](https://akash.network/rewards.
- The address of the provider.

For example:

```
echo 'participation: 3bif3qp17x22l' > founders/level3/akash.yourdomain.com
echo 'provider: 7e99e953d23570c2350ae6eee6937d00b6accc258f1904c4547b7aabd900b1dd' >> founders/level3/akash.yourdomain.com
```

Where `3bif3qp17x22l` is the participation id and `akash.yourdomain.com` is your domain. See [submissions](founders/level3) for examples.

4. Commit your code, and send a pull request to [ecosystem repo](https://github.com/ovrclk/ecosystem).

**Bonus Reward**: 25 AKTs

Bonus AKTs will be awarded to the community members that help us spread our vision for creating a truly open-source cloud. Sharing your experience on Twitter and tagging us will earn you an additional 25 AKT. Please note, this bonus is available only upon completion of the main challenge.

# Open Source Contributions

## <img src="https://cdn.simpleicons.org/nvidia/76B900" width="30" alt="NVIDIA"> NVIDIA · CCCL

<table>
<tr>
<td>

### Merge-path lower & upper bound

Added GPU search algorithms for sorted inputs.

**Up to 38× faster.**

</td>
<td width="150" align="center">

[PR #8780 ↗](https://github.com/NVIDIA/cccl/pull/8780)

</td>
</tr>
</table>

## <img src="https://cdn.simpleicons.org/pytorch/EE4C2C" width="30" alt="PyTorch"> PyTorch

<table>
<tr>
<td>

### Native Metal hardtanh backward

Replaced the MPSGraph implementation with a native Metal kernel.

</td>
<td width="150" align="center">

[PR #200791 ↗](https://github.com/pytorch/pytorch/pull/200791)

</td>
</tr>
<tr>
<td>

### Floating-point remainder correctness

Fixed errors for large quotients and infinite divisors on MPS.
Added regression tests against CPU results.

</td>
<td width="150" align="center">

[PR #200267 ↗](https://github.com/pytorch/pytorch/pull/200267)

</td>
</tr>
</table>

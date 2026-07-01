# MoA Decision 鈥?Mixture of Agents for OpenClaw

> 澶氳瑙掑苟琛屽垎鏋?鈫?鑱氬悎浜ゅ弶楠岃瘉 鈫?鏇村彲闈犵殑鍐崇瓥

## 杩欐槸浠€涔?
鍊熼壌 [Hermes Agent](https://hermes-agent.nousresearch.com/) 鐨?Mixture of Agents (MoA) 鏋舵瀯锛屽湪 OpenClaw 涓疄鐜板妯″瀷娣峰悎鍐崇瓥妯″紡銆?
闈㈠澶嶆潅闂鏃讹紝骞惰 spawn 澶氫釜 subagent 浠庝笉鍚岃瑙掔嫭绔嬪垎鏋愶紝涓?agent 鑱氬悎鍚勬柟瑙傜偣鍋氭渶缁堝喅绛栥€傛湁鏁堝噺灏戝崟涓€瑙嗚鐨勫亸瑙佸拰鐩插尯銆?
## 鏁堟灉

鍦ㄥ疄娴嬩腑锛?026骞?鏈堬級锛? 涓弬鑰?agent 鍒嗗埆浠庢妧鏈彲琛屾€с€佸晢涓氭ā寮忋€佸競鍦洪渶姹備笁涓瑙掑垎鏋愬悓涓€闂锛岃仛鍚堝悗锛?- 鉁?鎴愬姛杩囨护浜嗗崟妯″瀷鎺ㄨ崘浣嗕笉琚鏂硅鍙殑鏂瑰悜
- 鉁?涓夋柟鍏辫瘑鏂瑰悜淇″績鏄捐憲楂樹簬鍗曟ā鍨嬭緭鍑?- 鈿狅笍 娑堣€楃害 3x token锛岃€楁椂绾?40 绉?
## 瀹夎

灏?`moa-decision` 鏂囦欢澶瑰鍒跺埌 OpenClaw skills 鐩綍锛?
```
~/.openclaw-autoclaw/skills/moa-decision/
```

鎴栦娇鐢?ClawHub锛堝鏋滃凡鍙戝竷锛夛細

```bash
clawhub install moa-decision
```

## 浣跨敤

褰撻亣鍒板鏉傚喅绛栨椂锛宎gent 浼氳嚜鍔ㄨ瘑鍒苟瑙﹀彂 MoA 妯″紡锛?
1. **璇嗗埆闂** 鈥?鍒ゆ柇鏄惁闇€瑕佸瑙嗚鍒嗘瀽
2. **鎷嗚В瑙嗚** 鈥?鏍规嵁闂绫诲瀷鎷嗗嚭 2-4 涓嫭绔嬪垎鏋愯瑙?3. **骞惰鍒嗘瀽** 鈥?spawn 澶氫釜 subagent 鍒嗗埆浠庝笉鍚岃瑙掔嫭绔嬪垎鏋?4. **鑱氬悎姹囨€?* 鈥?涓?agent 浜ゅ弶瀵规瘮鍚勬柟瑙傜偣锛岃緭鍑鸿仛鍚堢粨璁?
### 鎵嬪姩瑙﹀彂

瀵?agent 璇达細
- "鐢?MoA 妯″紡鍒嗘瀽涓€涓嬭繖涓棶棰橈細..."
- "澶氳瑙掑垎鏋愪竴涓嬶細..."
- "浠庡涓搴﹁瘎浼颁竴涓嬶細..."

## 閰嶇疆

| 鍙傛暟 | 榛樿鍊?| 璇存槑 |
|------|--------|------|
| 鍙傝€?agent 鏁伴噺 | 3 | 骞宠　璐ㄩ噺鍜屾垚鏈?|
| 姣忎釜 agent 杈撳嚭 | 300-500 瀛?| 鎺у埗涓婁笅鏂囬暱搴?|
| 鎬?token 棰勭畻 | ~50k | 3 鍙傝€?+ 1 鑱氬悎 |

## 閫傜敤鍦烘櫙

- 鉁?鎶€鏈€夊瀷銆佹柟妗堝姣?- 鉁?鍟嗕笟鏂瑰悜璇勪及銆佹垬鐣ヨ鍒?- 鉁?鏋舵瀯璁捐璇勫
- 鉁?椋庨櫓璇勪及
- 鉂?绠€鍗曢棶绛斻€佹枃浠舵搷浣溿€佹悳绱换鍔?
## 鍙傝€?
- [Hermes Agent MoA 瀹樻柟鏂囨。](https://hermes-agent.nousresearch.com/docs/user-guide/features/mixture-of-agents)
- [Mixture of Agents 璁烘枃 (Together AI)](https://arxiv.org/abs/2406.04692)

## License

MIT


想想自己的分布式锁用在业务系统中，有没有高并发问题，如果有，如何用分段加锁思路来解决，或者用kv存储来存放实时库存抗并发，直接在kv里扣减，避免用分布式锁
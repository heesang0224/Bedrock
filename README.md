기본구성(afterEvents)
world.afterEvents.이벤트명.subscribe((event) => {
  // 이벤트 후 행동 정의
});



기본구성(afterEvents.blockExplode)


world.afterEvents.blockExplode.subscribe((event) => {
  const block = event.block;



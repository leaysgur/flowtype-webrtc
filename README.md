# flowtype-webrtc

Currently, Flow supports WebRTC related APIs below only.

- [getUserMedia()](https://github.com/facebook/flow/blob/master/lib/bom.js#L128)
- [MediaStream](https://github.com/facebook/flow/blob/master/lib/bom.js#L687)
- [MediaStreamTrack](https://github.com/facebook/flow/blob/master/lib/bom.js#L705)

On the other hand, built-in typings does not have definitions about `RTCPeerConnection`, `RTCSessionDescription`, and so on.

So, we need this repo until that day comes!

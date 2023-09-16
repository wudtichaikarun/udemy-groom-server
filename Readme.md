# gRPC server

## Architecture

![alt groom_rpc](/images/groom_rpc.png "groom gRPC Architecture")

## Start groom gRPC Server

```
dotnet run
```

## RegisterToRoom

1. Download program [bloomrpc](https://github.com/bloomrpc/bloomrpc/releases/tag/1.5.3).
2. import `groom.proto` for example `/Documents/poc/dotnet/groomserver/Protos/groom.proto`
3. edit room name
   example

```
{
  "room_name": "Cars"
}
```

4. click green button(play)

Note: before "RegisterToRoom" you have to "Start groom gRPC Server?

![alt register_to_room](/images/register_to_room.png "Register to room")

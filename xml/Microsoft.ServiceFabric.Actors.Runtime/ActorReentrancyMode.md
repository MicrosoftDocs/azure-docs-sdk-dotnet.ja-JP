<Type Name="ActorReentrancyMode" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode">
  <TypeSignature Language="C#" Value="public enum ActorReentrancyMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ActorReentrancyMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ActorReentrancyMode" />
  <TypeSignature Language="F#" Value="type ActorReentrancyMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="0b112-101">アクター メソッドの呼び出しのための再入モードを指定します。</span><span class="sxs-lookup"><span data-stu-id="0b112-101">Specifies Reentrancy mode for actor method calls.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Disallowed">
      <MemberSignature Language="C#" Value="Disallowed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode Disallowed = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode.Disallowed" />
      <MemberSignature Language="VB.NET" Value="Disallowed" />
      <MemberSignature Language="F#" Value="Disallowed = 2" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode.Disallowed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0b112-102">再入するアクターは許可されていません。</span><span class="sxs-lookup"><span data-stu-id="0b112-102">Disallows actors to be reentrant.</span></span> <span data-ttu-id="0b112-103">アクターは、他のアクター、型の例外を再入可能なメッセージを送信した場合は、このケースで<see cref="T:System.Fabric.FabricException" />がスローされます。</span><span class="sxs-lookup"><span data-stu-id="0b112-103">In this case if an actor sends a reentrant message to another actor, an exception of type <see cref="T:System.Fabric.FabricException" /> will be thrown.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="LogicalCallContext">
      <MemberSignature Language="C#" Value="LogicalCallContext" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode LogicalCallContext = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode.LogicalCallContext" />
      <MemberSignature Language="VB.NET" Value="LogicalCallContext" />
      <MemberSignature Language="F#" Value="LogicalCallContext = 1" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode.LogicalCallContext" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0b112-104">同じ呼び出しコンテキストのチェーン内にある場合に再入可能であるアクターを使用できます。</span><span class="sxs-lookup"><span data-stu-id="0b112-104">Allows actors to be reentrant if they are in the same call context chain.</span></span> <span data-ttu-id="0b112-105">これは、アクターの既定のオプションです。</span><span class="sxs-lookup"><span data-stu-id="0b112-105">This is the default option for actors.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>
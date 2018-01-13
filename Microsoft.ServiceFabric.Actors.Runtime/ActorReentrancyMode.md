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
            アクター メソッドの呼び出しのための再入モードを指定します。
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
            再入するアクターは許可されていません。 アクターは、他のアクター、型の例外を再入可能なメッセージを送信した場合は、このケースで<see cref="T:System.Fabric.FabricException" />がスローされます。
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
            同じ呼び出しコンテキストのチェーン内にある場合に再入可能であるアクターを使用できます。 これは、アクターの既定のオプションです。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>
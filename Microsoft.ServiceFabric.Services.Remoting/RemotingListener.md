<Type Name="RemotingListener" FullName="Microsoft.ServiceFabric.Services.Remoting.RemotingListener">
  <TypeSignature Language="C#" Value="public enum RemotingListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RemotingListener extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.RemotingListener" />
  <TypeSignature Language="VB.NET" Value="Public Enum RemotingListener" />
  <TypeSignature Language="F#" Value="type RemotingListener = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            リモート処理プロバイダー attribuite を使用して、リモート処理クライアントを決定する場合は、リモート処理スタック server/リスナーを決定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CompatListener">
      <MemberSignature Language="C#" Value="CompatListener" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingListener CompatListener = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Remoting.RemotingListener.CompatListener" />
      <MemberSignature Language="VB.NET" Value="CompatListener" />
      <MemberSignature Language="F#" Value="CompatListener = 1" Usage="Microsoft.ServiceFabric.Services.Remoting.RemotingListener.CompatListener" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingListener</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            V1 と V2 クライアントの両方をサポートするには、リスナーを作成する両方の V1 と V2 リスナーを作成するには、これが選択されています。
            これは、V1 から V2 リスナーへのアップグレードが発生した場合に便利です。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="V1Listener">
      <MemberSignature Language="C#" Value="V1Listener" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingListener V1Listener = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Remoting.RemotingListener.V1Listener" />
      <MemberSignature Language="VB.NET" Value="V1Listener" />
      <MemberSignature Language="F#" Value="V1Listener = 0" Usage="Microsoft.ServiceFabric.Services.Remoting.RemotingListener.V1Listener" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingListener</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            作成時にこの選択は、V1 Listener.V2、古い (すぐに推奨されていません) は、リモート処理スタックです。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="V2Listener">
      <MemberSignature Language="C#" Value="V2Listener" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingListener V2Listener = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Remoting.RemotingListener.V2Listener" />
      <MemberSignature Language="VB.NET" Value="V2Listener" />
      <MemberSignature Language="F#" Value="V2Listener = 2" Usage="Microsoft.ServiceFabric.Services.Remoting.RemotingListener.V2Listener" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingListener</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            作成時にこの選択は V2 Listener.V2 は新しいリモート処理スタックです。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>
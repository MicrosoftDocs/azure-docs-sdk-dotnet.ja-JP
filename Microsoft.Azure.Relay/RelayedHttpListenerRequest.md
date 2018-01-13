<Type Name="RelayedHttpListenerRequest" FullName="Microsoft.Azure.Relay.RelayedHttpListenerRequest">
  <TypeSignature Language="C#" Value="public sealed class RelayedHttpListenerRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RelayedHttpListenerRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.RelayedHttpListenerRequest" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RelayedHttpListenerRequest" />
  <TypeSignature Language="F#" Value="type RelayedHttpListenerRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            受信クライアント要求の説明、<see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" />オブジェクト。
            これは System.Net.HttpListenerRequest 後にモデル化されます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public System.Net.WebHeaderCollection Headers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Net.WebHeaderCollection Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayedHttpListenerRequest.Headers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Headers As WebHeaderCollection" />
      <MemberSignature Language="F#" Value="member this.Headers : System.Net.WebHeaderCollection" Usage="Microsoft.Azure.Relay.RelayedHttpListenerRequest.Headers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.WebHeaderCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求で受信したヘッダー名前/値ペアのコレクションを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public Uri Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayedHttpListenerRequest.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As Uri" />
      <MemberSignature Language="F#" Value="member this.Url : Uri" Usage="Microsoft.Azure.Relay.RelayedHttpListenerRequest.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クライアントによって要求された Uri を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
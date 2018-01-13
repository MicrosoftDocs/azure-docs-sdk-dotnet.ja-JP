<Type Name="RelayedHttpListenerResponse" FullName="Microsoft.Azure.Relay.RelayedHttpListenerResponse">
  <TypeSignature Language="C#" Value="public sealed class RelayedHttpListenerResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RelayedHttpListenerResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.RelayedHttpListenerResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RelayedHttpListenerResponse" />
  <TypeSignature Language="F#" Value="type RelayedHttpListenerResponse = class" />
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
            によって処理される要求に応答を表します、<see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" />オブジェクト。
            これは System.Net.HttpListenerResponse 後にモデル化されます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public System.Net.WebHeaderCollection Headers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Net.WebHeaderCollection Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayedHttpListenerResponse.Headers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Headers As WebHeaderCollection" />
      <MemberSignature Language="F#" Value="member this.Headers : System.Net.WebHeaderCollection" Usage="Microsoft.Azure.Relay.RelayedHttpListenerResponse.Headers" />
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
            このリスナーによって返されるヘッダーの名前/値ペアのコレクションを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public System.Net.HttpStatusCode StatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.HttpStatusCode StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayedHttpListenerResponse.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusCode As HttpStatusCode" />
      <MemberSignature Language="F#" Value="member this.StatusCode : System.Net.HttpStatusCode with get, set" Usage="Microsoft.Azure.Relay.RelayedHttpListenerResponse.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpStatusCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>クライアントへ返される HTTP ステータス コードを取得または設定します。</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">オブジェクトが閉じています。</exception>
        <exception cref="T:System.Net.ProtocolViolationException">設定操作として指定した値が無効です。 有効な値は 100 から 999 の範囲です。</exception>
      </Docs>
    </Member>
    <Member MemberName="StatusDescription">
      <MemberSignature Language="C#" Value="public string StatusDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayedHttpListenerResponse.StatusDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusDescription As String" />
      <MemberSignature Language="F#" Value="member this.StatusDescription : string with get, set" Usage="Microsoft.Azure.Relay.RelayedHttpListenerResponse.StatusDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>クライアントへ返される HTTP ステータス コードの説明テキストを取得または設定します。</summary>
        <value>クライアントに返される HTTP ステータス コードの説明文です。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">設定操作に指定された値が null です。</exception>
        <exception cref="T:System.ArgumentException">設定操作として指定した値に印刷できない文字が含まれます。</exception>
      </Docs>
    </Member>
  </Members>
</Type>
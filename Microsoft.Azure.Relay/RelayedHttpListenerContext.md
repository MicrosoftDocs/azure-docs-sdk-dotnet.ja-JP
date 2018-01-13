<Type Name="RelayedHttpListenerContext" FullName="Microsoft.Azure.Relay.RelayedHttpListenerContext">
  <TypeSignature Language="C#" Value="public class RelayedHttpListenerContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RelayedHttpListenerContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.RelayedHttpListenerContext" />
  <TypeSignature Language="VB.NET" Value="Public Class RelayedHttpListenerContext" />
  <TypeSignature Language="F#" Value="type RelayedHttpListenerContext = class" />
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
            クライアント要求を表す要求と応答のオブジェクトへのアクセスを提供する<see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" />です。
            これは System.Net.HttpListenerContext 後にモデル化されます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Request">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Relay.RelayedHttpListenerRequest Request { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Relay.RelayedHttpListenerRequest Request" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayedHttpListenerContext.Request" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Request As RelayedHttpListenerRequest" />
      <MemberSignature Language="F#" Value="member this.Request : Microsoft.Azure.Relay.RelayedHttpListenerRequest" Usage="Microsoft.Azure.Relay.RelayedHttpListenerContext.Request" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Relay.RelayedHttpListenerRequest</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クライアントのリソース要求を表す <see cref="T:Microsoft.Azure.Relay.RelayedHttpListenerRequest" /> を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Relay.RelayedHttpListenerResponse Response { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Relay.RelayedHttpListenerResponse Response" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayedHttpListenerContext.Response" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Response As RelayedHttpListenerResponse" />
      <MemberSignature Language="F#" Value="member this.Response : Microsoft.Azure.Relay.RelayedHttpListenerResponse" Usage="Microsoft.Azure.Relay.RelayedHttpListenerContext.Response" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Relay.RelayedHttpListenerResponse</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="T:Microsoft.Azure.Relay.RelayedHttpListenerResponse" />クライアントの要求に対する応答を制御するオブジェクト。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayedHttpListenerContext.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="relayedHttpListenerContext.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在のオブジェクトを表す文字列を返します。  エンド ツー エンドの相関関係の TrackingId が含まれます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
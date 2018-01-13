<Type Name="NonDualMessageSecurityOverRelayHttp" FullName="Microsoft.ServiceBus.NonDualMessageSecurityOverRelayHttp">
  <TypeSignature Language="C#" Value="public sealed class NonDualMessageSecurityOverRelayHttp : Microsoft.ServiceBus.MessageSecurityOverRelayHttp" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NonDualMessageSecurityOverRelayHttp extends Microsoft.ServiceBus.MessageSecurityOverRelayHttp" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NonDualMessageSecurityOverRelayHttp" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NonDualMessageSecurityOverRelayHttp&#xA;Inherits MessageSecurityOverRelayHttp" />
  <TypeSignature Language="F#" Value="type NonDualMessageSecurityOverRelayHttp = class&#xA;    inherit MessageSecurityOverRelayHttp" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.MessageSecurityOverRelayHttp</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="54d2f-101">WS Http リレー バインドのメッセージ レベルのセキュリティ プロパティを設定できます。</span><span class="sxs-lookup"><span data-stu-id="54d2f-101">Enables setting message-level security properties for a WS-Http relay binding.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EstablishSecurityContext">
      <MemberSignature Language="C#" Value="public bool EstablishSecurityContext { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EstablishSecurityContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NonDualMessageSecurityOverRelayHttp.EstablishSecurityContext" />
      <MemberSignature Language="VB.NET" Value="Public Property EstablishSecurityContext As Boolean" />
      <MemberSignature Language="F#" Value="member this.EstablishSecurityContext : bool with get, set" Usage="Microsoft.ServiceBus.NonDualMessageSecurityOverRelayHttp.EstablishSecurityContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="54d2f-102">取得またはセキュリティ コンテキスト トークンが確立されるかどうかを指定する値を設定します。</span><span class="sxs-lookup"><span data-stu-id="54d2f-102">Gets or sets a value that specifies whether a security context token is established.</span></span></summary>
        <value><span data-ttu-id="54d2f-103">セキュリティ コンテキスト トークンが確立される場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="54d2f-103">true if the security context token is established; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSecureConversationEnabled">
      <MemberSignature Language="C#" Value="protected override bool IsSecureConversationEnabled ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool IsSecureConversationEnabled() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NonDualMessageSecurityOverRelayHttp.IsSecureConversationEnabled" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function IsSecureConversationEnabled () As Boolean" />
      <MemberSignature Language="F#" Value="override this.IsSecureConversationEnabled : unit -&gt; bool" Usage="nonDualMessageSecurityOverRelayHttp.IsSecureConversationEnabled " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="54d2f-104">セキュリティで保護されたメッセージ交換が有効になっているかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="54d2f-104">Gets a value indicating whether secure conversation is enabled.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
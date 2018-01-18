<Type Name="IWithFrontend&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithFrontend&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithFrontend&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontend`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithFrontend`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontend(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithFrontend&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="f1959-101">この定義をアタッチした後に戻るには、親アプリケーション ゲートウェイ定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="f1959-101">The stage of the parent application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="f1959-102">関連付けるリスナーが、フロント エンド IP 構成を指定できるようにアプリケーション ゲートウェイ フロント エンド リスナー定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="f1959-102">The stage of an application gateway frontend listener definition allowing to specify the frontend IP configuration to associate the listener with.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithFrontendPort&lt;ParentT&gt; WithPrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithFrontendPort`1&lt;!ParentT&gt; WithPrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithFrontend`1.WithPrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateFrontend () As IWithFrontendPort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithFrontendPort&lt;'ParentT&gt;" Usage="iWithFrontend.WithPrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithFrontendPort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f1959-103">アプリケーション ゲートウェイのプライベート (内部) フロント エンド、リスナーに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="f1959-103">Associates the listener with the application gateway's private (internal) frontend.</span></span>
            <span data-ttu-id="f1959-104">プライベート フロント エンドがまだ存在しない場合、自動生成された名前の下に作成およびアプリケーション ゲートウェイのサブネットに関連付けられたするされます。</span><span class="sxs-lookup"><span data-stu-id="f1959-104">If the private frontend does not exist yet, it will be created under an auto-generated name and associated with the application gateway's subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f1959-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f1959-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithFrontendPort&lt;ParentT&gt; WithPublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithFrontendPort`1&lt;!ParentT&gt; WithPublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithFrontend`1.WithPublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicFrontend () As IWithFrontendPort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithFrontendPort&lt;'ParentT&gt;" Usage="iWithFrontend.WithPublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithFrontendPort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f1959-106">アプリケーション ゲートウェイのパブリック (インターネット側) フロント エンド、リスナーに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="f1959-106">Associates the listener with the application gateway's public (Internet-facing) frontend.</span></span>
            <span data-ttu-id="f1959-107">パブリック フロント エンドがまだ存在しない場合、自動生成された名前の下に作成およびアプリケーション ゲートウェイのパブリック IP アドレスに関連付けられているされます。</span><span class="sxs-lookup"><span data-stu-id="f1959-107">If the public frontend does not exist yet, it will be created under an auto-generated name and associated with the application gateway's public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f1959-108">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f1959-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>
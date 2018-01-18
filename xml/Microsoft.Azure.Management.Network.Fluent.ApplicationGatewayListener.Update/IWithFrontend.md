<Type Name="IWithFrontend" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IWithFrontend">
  <TypeSignature Language="C#" Value="public interface IWithFrontend" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontend" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IWithFrontend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontend" />
  <TypeSignature Language="F#" Value="type IWithFrontend = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1bb32-101">アプリケーション ゲートウェイのフロント エンド リスナーのステージにリスナーを関連付けるには、フロント エンド IP 構成を指定する許可を更新します。</span><span class="sxs-lookup"><span data-stu-id="1bb32-101">The stage of an application gateway frontend listener update allowing to specify the frontend IP configuration to associate the listener with.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate WithPrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate WithPrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IWithFrontend.WithPrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateFrontend () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate" Usage="iWithFrontend.WithPrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1bb32-102">アプリケーション ゲートウェイのプライベート (内部) フロント エンド、リスナーに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="1bb32-102">Associates the listener with the application gateway's private (internal) frontend.</span></span>
            <span data-ttu-id="1bb32-103">プライベート フロント エンドがまだ存在しない場合、自動生成された名前の下に作成およびアプリケーション ゲートウェイのサブネットに関連付けられたするされます。</span><span class="sxs-lookup"><span data-stu-id="1bb32-103">If the private frontend does not exist yet, it will be created under an auto-generated name and associated with the application gateway's subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1bb32-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="1bb32-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate WithPublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate WithPublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IWithFrontend.WithPublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicFrontend () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate" Usage="iWithFrontend.WithPublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1bb32-105">アプリケーション ゲートウェイのパブリック (インターネット側) フロント エンド、リスナーに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="1bb32-105">Associates the listener with the application gateway's public (Internet-facing) frontend.</span></span>
            <span data-ttu-id="1bb32-106">パブリック フロント エンドがまだ存在しない場合、自動生成された名前の下に作成およびアプリケーション ゲートウェイのパブリック IP アドレスに関連付けられているされます。</span><span class="sxs-lookup"><span data-stu-id="1bb32-106">If the public frontend does not exist yet, it will be created under an auto-generated name and associated with the application gateway's public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1bb32-107">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="1bb32-107">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>
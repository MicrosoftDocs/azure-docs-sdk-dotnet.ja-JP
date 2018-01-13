<Type Name="IWithSize" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithSize">
  <TypeSignature Language="C#" Value="public interface IWithSize" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSize" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithSize" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSize" />
  <TypeSignature Language="F#" Value="type IWithSize = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="576fa-101">アプリケーション ゲートウェイの更新を許可するサイズを指定する段階です。</span><span class="sxs-lookup"><span data-stu-id="576fa-101">The stage of an application gateway update allowing to specify the size.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSize">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithSize (Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySkuName size);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithSize(class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySkuName size) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithSize.WithSize(Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySkuName)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSize (size As ApplicationGatewaySkuName) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithSize : Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySkuName -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate" Usage="iWithSize.WithSize size" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="size" Type="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySkuName" />
      </Parameters>
      <Docs>
        <param name="size"><span data-ttu-id="576fa-102">アプリケーション ゲートウェイ SKU の名前。</span><span class="sxs-lookup"><span data-stu-id="576fa-102">An application gateway SKU name.</span></span></param>
        <summary>
            <span data-ttu-id="576fa-103">選択したレベルのコンテキスト内で作成するには、そのアプリケーション ゲートウェイのサイズを指定します。</span><span class="sxs-lookup"><span data-stu-id="576fa-103">Specifies the size of the application gateway to create within the context of the selected tier.</span></span>
            <span data-ttu-id="576fa-104">既定では、最小サイズは使用されます。</span><span class="sxs-lookup"><span data-stu-id="576fa-104">By default, the smallest size is used.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="576fa-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="576fa-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>
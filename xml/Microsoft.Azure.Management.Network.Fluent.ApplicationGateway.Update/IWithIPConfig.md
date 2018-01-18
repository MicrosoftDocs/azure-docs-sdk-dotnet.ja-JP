<Type Name="IWithIPConfig" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig">
  <TypeSignature Language="C#" Value="public interface IWithIPConfig" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIPConfig" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIPConfig" />
  <TypeSignature Language="F#" Value="type IWithIPConfig = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="451f9-101">アプリケーション ゲートウェイの更新を許可する IP 構成を変更する段階です。</span><span class="sxs-lookup"><span data-stu-id="451f9-101">The stage of an application gateway update allowing to modify IP configurations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineDefaultIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineDefaultIPConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineDefaultIPConfiguration() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig.DefineDefaultIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineDefaultIPConfiguration () As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineDefaultIPConfiguration : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithIPConfig.DefineDefaultIPConfiguration " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="451f9-102">既定の IP 構成の定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="451f9-102">Begins the definition of the default IP configuration.</span></span>
            <span data-ttu-id="451f9-103">これに相当がありますが、既定の IP 構成に対して既に存在する場合、<code>updateDefaultIPConfiguration()</code>です。</span><span class="sxs-lookup"><span data-stu-id="451f9-103">If a default IP configuration already exists, it will be this is equivalent to <code>updateDefaultIPConfiguration()</code>.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="451f9-104">IP 構成の更新の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="451f9-104">The first stage of an IP configuration update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateDefaultIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate UpdateDefaultIPConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate UpdateDefaultIPConfiguration() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig.UpdateDefaultIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateDefaultIPConfiguration () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateDefaultIPConfiguration : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate" Usage="iWithIPConfig.UpdateDefaultIPConfiguration " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="451f9-105">既定の IP 構成、1 つしかないと仮定した場合に存在する 1 つだけの IP 構成などの更新を開始します。</span><span class="sxs-lookup"><span data-stu-id="451f9-105">Begins the update of the default IP configuration i.e. the only one IP configuration that exists, assuming only one exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="451f9-106">IP 構成の更新の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="451f9-106">The first stage of an IP configuration update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate UpdateIPConfiguration (string ipConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate UpdateIPConfiguration(string ipConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig.UpdateIPConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateIPConfiguration (ipConfigurationName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateIPConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate" Usage="iWithIPConfig.UpdateIPConfiguration ipConfigurationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipConfigurationName"><span data-ttu-id="451f9-107">既存の IP 構成の名前。</span><span class="sxs-lookup"><span data-stu-id="451f9-107">The name of an existing IP configuration.</span></span></param>
        <summary>
            <span data-ttu-id="451f9-108">既存の IP 構成の更新を開始します。</span><span class="sxs-lookup"><span data-stu-id="451f9-108">Begins the update of an existing IP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="451f9-109">IP 構成の更新の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="451f9-109">The first stage of an IP configuration update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutIPConfiguration (string ipConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutIPConfiguration(string ipConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig.WithoutIPConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutIPConfiguration (ipConfigurationName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutIPConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithIPConfig.WithoutIPConfiguration ipConfigurationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipConfigurationName"><span data-ttu-id="451f9-110">削除する IP 構成の名前。</span><span class="sxs-lookup"><span data-stu-id="451f9-110">The name of the IP configuration to remove.</span></span></param>
        <summary>
            <span data-ttu-id="451f9-111">指定された IP 構成を削除します。</span><span class="sxs-lookup"><span data-stu-id="451f9-111">Removes the specified IP configuration.</span></span>
            <span data-ttu-id="451f9-112">他の設定で参照されている IP 構成を削除すると、アプリケーション ゲートウェイが分割することに注意してください。</span><span class="sxs-lookup"><span data-stu-id="451f9-112">Note that removing an IP configuration referenced by other settings may break the application gateway.</span></span>
            <span data-ttu-id="451f9-113">また、関数には、そのアプリケーション ゲートウェイの少なくとも 1 つの IP 構成が必要があります。</span><span class="sxs-lookup"><span data-stu-id="451f9-113">Also, there must be at least one IP configuration for the application gateway to function.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="451f9-114">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="451f9-114">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>
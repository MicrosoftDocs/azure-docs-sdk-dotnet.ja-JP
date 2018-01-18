<Type Name="IWithConfiguration" FullName="Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithConfiguration">
  <TypeSignature Language="C#" Value="public interface IWithConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithConfiguration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithConfiguration" />
  <TypeSignature Language="F#" Value="type IWithConfiguration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ec092-101">複製元を指定する構成を許可するデプロイ スロット定義します。</span><span class="sxs-lookup"><span data-stu-id="ec092-101">A deployment slot definition allowing the configuration to clone from to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithBrandNewConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate WithBrandNewConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate WithBrandNewConfiguration() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithConfiguration.WithBrandNewConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Function WithBrandNewConfiguration () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithBrandNewConfiguration : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate" Usage="iWithConfiguration.WithBrandNewConfiguration " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ec092-102">新しいサイトの構成をデプロイ スロットを作成します。</span><span class="sxs-lookup"><span data-stu-id="ec092-102">Creates the deployment slot with brand new site configurations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ec092-103">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ec092-103">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithConfigurationFromDeploymentSlot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate WithConfigurationFromDeploymentSlot (Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot deploymentSlot);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate WithConfigurationFromDeploymentSlot(class Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot deploymentSlot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithConfiguration.WithConfigurationFromDeploymentSlot(Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithConfigurationFromDeploymentSlot (deploymentSlot As IDeploymentSlot) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithConfigurationFromDeploymentSlot : Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot -&gt; Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate" Usage="iWithConfiguration.WithConfigurationFromDeploymentSlot deploymentSlot" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deploymentSlot" Type="Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot" />
      </Parameters>
      <Docs>
        <param name="deploymentSlot"><span data-ttu-id="ec092-104">デプロイ スロットから構成のコピーをします。</span><span class="sxs-lookup"><span data-stu-id="ec092-104">The deployment slot to copy the configurations from.</span></span></param>
        <summary>
            <span data-ttu-id="ec092-105">指定したデプロイ スロットからサイトの構成をコピーします。</span><span class="sxs-lookup"><span data-stu-id="ec092-105">Copies the site configurations from a given deployment slot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ec092-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ec092-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithConfigurationFromParent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate WithConfigurationFromParent ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate WithConfigurationFromParent() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithConfiguration.WithConfigurationFromParent" />
      <MemberSignature Language="VB.NET" Value="Public Function WithConfigurationFromParent () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithConfigurationFromParent : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate" Usage="iWithConfiguration.WithConfigurationFromParent " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ec092-107">Web アプリは、デプロイ スロットからサイトの構成のコピーに属しています。</span><span class="sxs-lookup"><span data-stu-id="ec092-107">Copies the site configurations from the web app the deployment slot belongs to.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ec092-108">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ec092-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithConfigurationFromWebApp">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate WithConfigurationFromWebApp (Microsoft.Azure.Management.AppService.Fluent.IWebApp webApp);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate WithConfigurationFromWebApp(class Microsoft.Azure.Management.AppService.Fluent.IWebApp webApp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithConfiguration.WithConfigurationFromWebApp(Microsoft.Azure.Management.AppService.Fluent.IWebApp)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithConfigurationFromWebApp (webApp As IWebApp) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithConfigurationFromWebApp : Microsoft.Azure.Management.AppService.Fluent.IWebApp -&gt; Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate" Usage="iWithConfiguration.WithConfigurationFromWebApp webApp" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webApp" Type="Microsoft.Azure.Management.AppService.Fluent.IWebApp" />
      </Parameters>
      <Docs>
        <param name="webApp"><span data-ttu-id="ec092-109">構成をコピーする web アプリです。</span><span class="sxs-lookup"><span data-stu-id="ec092-109">The web app to copy the configurations from.</span></span></param>
        <summary>
            <span data-ttu-id="ec092-110">指定された web アプリからのサイト構成をコピーします。</span><span class="sxs-lookup"><span data-stu-id="ec092-110">Copies the site configurations from a given web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ec092-111">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ec092-111">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>
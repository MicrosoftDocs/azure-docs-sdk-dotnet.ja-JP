<Type Name="IWithDockerContainerImage" FullName="Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithDockerContainerImage">
  <TypeSignature Language="C#" Value="public interface IWithDockerContainerImage" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDockerContainerImage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithDockerContainerImage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDockerContainerImage" />
  <TypeSignature Language="F#" Value="type IWithDockerContainerImage = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3d2cf-101">Web アプリを指定する許可の docker イメージ ソースを更新します。</span><span class="sxs-lookup"><span data-stu-id="3d2cf-101">A web app update allowing docker image source to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithBuiltInImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate WithBuiltInImage (Microsoft.Azure.Management.AppService.Fluent.RuntimeStack runtimeStack);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate WithBuiltInImage(class Microsoft.Azure.Management.AppService.Fluent.RuntimeStack runtimeStack) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithDockerContainerImage.WithBuiltInImage(Microsoft.Azure.Management.AppService.Fluent.RuntimeStack)" />
      <MemberSignature Language="F#" Value="abstract member WithBuiltInImage : Microsoft.Azure.Management.AppService.Fluent.RuntimeStack -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate" Usage="iWithDockerContainerImage.WithBuiltInImage runtimeStack" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="runtimeStack" Type="Microsoft.Azure.Management.AppService.Fluent.RuntimeStack" />
      </Parameters>
      <Docs>
        <param name="runtimeStack"><span data-ttu-id="3d2cf-102">イメージにインストールされているランタイム スタック。</span><span class="sxs-lookup"><span data-stu-id="3d2cf-102">The runtime stack installed on the image.</span></span></param>
        <summary>
            <span data-ttu-id="3d2cf-103">いずれかで、作成する docker コンテナー イメージを指定します。</span><span class="sxs-lookup"><span data-stu-id="3d2cf-103">Specifies the docker container image to be a built in one.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3d2cf-104">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="3d2cf-104">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPrivateDockerHubImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials WithPrivateDockerHubImage (string imageAndTag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials WithPrivateDockerHubImage(string imageAndTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithDockerContainerImage.WithPrivateDockerHubImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateDockerHubImage (imageAndTag As String) As IWithCredentials" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateDockerHubImage : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials" Usage="iWithDockerContainerImage.WithPrivateDockerHubImage imageAndTag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageAndTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageAndTag"><span data-ttu-id="3d2cf-105">イメージと省略可能なタグ (たとえば ' イメージ: タグ ')。</span><span class="sxs-lookup"><span data-stu-id="3d2cf-105">Image and optional tag (eg 'image:tag').</span></span></param>
        <summary>
            <span data-ttu-id="3d2cf-106">Docker Hub からいずれかに docker コンテナー イメージを指定します。</span><span class="sxs-lookup"><span data-stu-id="3d2cf-106">Specifies the docker container image to be one from Docker Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3d2cf-107">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="3d2cf-107">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPrivateRegistryImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials WithPrivateRegistryImage (string imageAndTag, string serverUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials WithPrivateRegistryImage(string imageAndTag, string serverUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithDockerContainerImage.WithPrivateRegistryImage(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateRegistryImage (imageAndTag As String, serverUrl As String) As IWithCredentials" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateRegistryImage : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials" Usage="iWithDockerContainerImage.WithPrivateRegistryImage (imageAndTag, serverUrl)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageAndTag" Type="System.String" />
        <Parameter Name="serverUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageAndTag"><span data-ttu-id="3d2cf-108">イメージと省略可能なタグ (たとえば ' イメージ: タグ ')。</span><span class="sxs-lookup"><span data-stu-id="3d2cf-108">Image and optional tag (eg 'image:tag').</span></span></param>
        <param name="serverUrl"><span data-ttu-id="3d2cf-109">サーバーの URL をプライベート レジストリです。</span><span class="sxs-lookup"><span data-stu-id="3d2cf-109">The URL to the private registry server.</span></span></param>
        <summary>
            <span data-ttu-id="3d2cf-110">プライベート レジストリからいずれかに docker コンテナー イメージを指定します。</span><span class="sxs-lookup"><span data-stu-id="3d2cf-110">Specifies the docker container image to be one from a private registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3d2cf-111">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="3d2cf-111">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicDockerHubImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithStartUpCommand WithPublicDockerHubImage (string imageAndTag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithStartUpCommand WithPublicDockerHubImage(string imageAndTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithDockerContainerImage.WithPublicDockerHubImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicDockerHubImage (imageAndTag As String) As IWithStartUpCommand" />
      <MemberSignature Language="F#" Value="abstract member WithPublicDockerHubImage : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithStartUpCommand" Usage="iWithDockerContainerImage.WithPublicDockerHubImage imageAndTag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithStartUpCommand</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageAndTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageAndTag"><span data-ttu-id="3d2cf-112">イメージと省略可能なタグ (たとえば ' イメージ: タグ ')。</span><span class="sxs-lookup"><span data-stu-id="3d2cf-112">Image and optional tag (eg 'image:tag').</span></span></param>
        <summary>
            <span data-ttu-id="3d2cf-113">Docker Hub からいずれかに docker コンテナー イメージを指定します。</span><span class="sxs-lookup"><span data-stu-id="3d2cf-113">Specifies the docker container image to be one from Docker Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3d2cf-114">Web アプリの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="3d2cf-114">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>
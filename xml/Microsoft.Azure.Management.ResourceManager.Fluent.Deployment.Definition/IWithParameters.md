<Type Name="IWithParameters" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters">
  <TypeSignature Language="C#" Value="public interface IWithParameters" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithParameters" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithParameters" />
  <TypeSignature Language="F#" Value="type IWithParameters = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="be81d-101">パラメーターを指定するを許可する展開の定義。</span><span class="sxs-lookup"><span data-stu-id="be81d-101">A deployment definition allowing the parameters to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithParameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithMode WithParameters (object parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithMode WithParameters(object parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters.WithParameters(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithParameters (parameters As Object) As IWithMode" />
      <MemberSignature Language="F#" Value="abstract member WithParameters : obj -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithMode" Usage="iWithParameters.WithParameters parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithMode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="parameters"><span data-ttu-id="be81d-102">オブジェクト</span><span class="sxs-lookup"><span data-stu-id="be81d-102">the object</span></span></param>
        <summary>
            <span data-ttu-id="be81d-103">オブジェクトとしてパラメーターを指定します。</span><span class="sxs-lookup"><span data-stu-id="be81d-103">Specifies the parameters as an object.</span></span>
            </summary>
        <returns><span data-ttu-id="be81d-104">展開の定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="be81d-104">the next stage of the deployment definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithParameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithMode WithParameters (string parametersJson);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithMode WithParameters(string parametersJson) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters.WithParameters(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithParameters (parametersJson As String) As IWithMode" />
      <MemberSignature Language="F#" Value="abstract member WithParameters : string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithMode" Usage="iWithParameters.WithParameters parametersJson" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithMode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parametersJson" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parametersJson"><span data-ttu-id="be81d-105">parametersJson JSON 文字列</span><span class="sxs-lookup"><span data-stu-id="be81d-105">parametersJson the JSON string</span></span></param>
        <summary>
            <span data-ttu-id="be81d-106">JSON 文字列として、パラメーターを指定します。</span><span class="sxs-lookup"><span data-stu-id="be81d-106">Specifies the parameters as a JSON string.</span></span>
            </summary>
        <returns><span data-ttu-id="be81d-107">展開の定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="be81d-107">the next stage of the deployment definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithParametersLink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithMode WithParametersLink (string uri, string contentVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithMode WithParametersLink(string uri, string contentVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters.WithParametersLink(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithParametersLink (uri As String, contentVersion As String) As IWithMode" />
      <MemberSignature Language="F#" Value="abstract member WithParametersLink : string * string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithMode" Usage="iWithParameters.WithParametersLink (uri, contentVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithMode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.String" />
        <Parameter Name="contentVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="be81d-108">uri パラメーターをリモート ファイルの場所</span><span class="sxs-lookup"><span data-stu-id="be81d-108">uri the location of the remote parameters file</span></span></param>
        <param name="contentVersion"><span data-ttu-id="be81d-109">contentVersion パラメーター ファイルのバージョン</span><span class="sxs-lookup"><span data-stu-id="be81d-109">contentVersion the version of the parameters file</span></span></param>
        <summary>
            <span data-ttu-id="be81d-110">URL としてパラメーターを指定します。</span><span class="sxs-lookup"><span data-stu-id="be81d-110">Specifies the parameters as a URL.</span></span>
            </summary>
        <returns><span data-ttu-id="be81d-111">展開の定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="be81d-111">the next stage of the deployment definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
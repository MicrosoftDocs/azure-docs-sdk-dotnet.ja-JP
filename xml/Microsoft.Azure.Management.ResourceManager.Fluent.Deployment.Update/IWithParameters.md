<Type Name="IWithParameters" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IWithParameters">
  <TypeSignature Language="C#" Value="public interface IWithParameters" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithParameters" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IWithParameters" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithParameters" />
  <TypeSignature Language="F#" Value="type IWithParameters = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="97eed-101">パラメーターを変更できるようにする展開の更新。</span><span class="sxs-lookup"><span data-stu-id="97eed-101">A deployment update allowing to change the parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithParameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithParameters (object parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithParameters(object parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IWithParameters.WithParameters(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithParameters (parameters As Object) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithParameters : obj -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate" Usage="iWithParameters.WithParameters parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="parameters"><span data-ttu-id="97eed-102">オブジェクト</span><span class="sxs-lookup"><span data-stu-id="97eed-102">the object</span></span></param>
        <summary>
            <span data-ttu-id="97eed-103">オブジェクトとしてパラメーターを指定します。</span><span class="sxs-lookup"><span data-stu-id="97eed-103">Specifies the parameters as an object.</span></span>
            </summary>
        <returns><span data-ttu-id="97eed-104">更新プログラムの展開の次のステージ</span><span class="sxs-lookup"><span data-stu-id="97eed-104">the next stage of the deployment update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithParameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithParameters (string parametersJson);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithParameters(string parametersJson) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IWithParameters.WithParameters(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithParameters (parametersJson As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithParameters : string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate" Usage="iWithParameters.WithParameters parametersJson" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parametersJson" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parametersJson"><span data-ttu-id="97eed-105">parametersJson JSON 文字列</span><span class="sxs-lookup"><span data-stu-id="97eed-105">parametersJson the JSON string</span></span></param>
        <summary>
            <span data-ttu-id="97eed-106">JSON 文字列として、パラメーターを指定します。</span><span class="sxs-lookup"><span data-stu-id="97eed-106">Specifies the parameters as a JSON string.</span></span>
            </summary>
        <returns><span data-ttu-id="97eed-107">更新プログラムの展開の次のステージ</span><span class="sxs-lookup"><span data-stu-id="97eed-107">the next stage of the deployment update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithParametersLink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithParametersLink (string uri, string contentVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate WithParametersLink(string uri, string contentVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IWithParameters.WithParametersLink(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithParametersLink (uri As String, contentVersion As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithParametersLink : string * string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate" Usage="iWithParameters.WithParametersLink (uri, contentVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.String" />
        <Parameter Name="contentVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="97eed-108">uri パラメーターをリモート ファイルの場所</span><span class="sxs-lookup"><span data-stu-id="97eed-108">uri the location of the remote parameters file</span></span></param>
        <param name="contentVersion"><span data-ttu-id="97eed-109">contentVersion パラメーター ファイルのバージョン</span><span class="sxs-lookup"><span data-stu-id="97eed-109">contentVersion the version of the parameters file</span></span></param>
        <summary>
            <span data-ttu-id="97eed-110">URL としてパラメーターを指定します。</span><span class="sxs-lookup"><span data-stu-id="97eed-110">Specifies the parameters as a URL.</span></span>
            </summary>
        <returns><span data-ttu-id="97eed-111">更新プログラムの展開の次のステージ</span><span class="sxs-lookup"><span data-stu-id="97eed-111">the next stage of the deployment update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
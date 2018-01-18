<Type Name="IWithTemplate" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate">
  <TypeSignature Language="C#" Value="public interface IWithTemplate" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTemplate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTemplate" />
  <TypeSignature Language="F#" Value="type IWithTemplate = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1c1d7-101">新しい展開の定義を指定するテンプレートを許可します。</span><span class="sxs-lookup"><span data-stu-id="1c1d7-101">A deployment definition allowing the template to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTemplate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters WithTemplate (object template);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters WithTemplate(object template) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate.WithTemplate(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTemplate (template As Object) As IWithParameters" />
      <MemberSignature Language="F#" Value="abstract member WithTemplate : obj -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters" Usage="iWithTemplate.WithTemplate template" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="template" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="template"><span data-ttu-id="1c1d7-102">オブジェクト</span><span class="sxs-lookup"><span data-stu-id="1c1d7-102">the object</span></span></param>
        <summary>
            <span data-ttu-id="1c1d7-103">オブジェクトとしてテンプレートを指定します。</span><span class="sxs-lookup"><span data-stu-id="1c1d7-103">Specifies the template as an object.</span></span>
            </summary>
        <returns><span data-ttu-id="1c1d7-104">展開の定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="1c1d7-104">the next stage of the deployment definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithTemplate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters WithTemplate (string templateJson);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters WithTemplate(string templateJson) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate.WithTemplate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTemplate (templateJson As String) As IWithParameters" />
      <MemberSignature Language="F#" Value="abstract member WithTemplate : string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters" Usage="iWithTemplate.WithTemplate templateJson" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="templateJson" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="templateJson"><span data-ttu-id="1c1d7-105">templateJson JSON 文字列</span><span class="sxs-lookup"><span data-stu-id="1c1d7-105">templateJson the JSON string</span></span></param>
        <summary>
            <span data-ttu-id="1c1d7-106">JSON 文字列としてテンプレートを指定します。</span><span class="sxs-lookup"><span data-stu-id="1c1d7-106">Specifies the template as a JSON string.</span></span>
            </summary>
        <returns><span data-ttu-id="1c1d7-107">展開の定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="1c1d7-107">the next stage of the deployment definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithTemplateLink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters WithTemplateLink (string uri, string contentVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters WithTemplateLink(string uri, string contentVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate.WithTemplateLink(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTemplateLink (uri As String, contentVersion As String) As IWithParameters" />
      <MemberSignature Language="F#" Value="abstract member WithTemplateLink : string * string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters" Usage="iWithTemplate.WithTemplateLink (uri, contentVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.String" />
        <Parameter Name="contentVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="1c1d7-108">リモートのテンプレート ファイルの場所の uri</span><span class="sxs-lookup"><span data-stu-id="1c1d7-108">uri the location of the remote template file</span></span></param>
        <param name="contentVersion"><span data-ttu-id="1c1d7-109">contentVersion テンプレート ファイルのバージョン</span><span class="sxs-lookup"><span data-stu-id="1c1d7-109">contentVersion the version of the template file</span></span></param>
        <summary>
            <span data-ttu-id="1c1d7-110">URL としてテンプレートを指定します。</span><span class="sxs-lookup"><span data-stu-id="1c1d7-110">Specifies the template as a URL.</span></span>
            </summary>
        <returns><span data-ttu-id="1c1d7-111">展開の定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="1c1d7-111">the next stage of the deployment definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
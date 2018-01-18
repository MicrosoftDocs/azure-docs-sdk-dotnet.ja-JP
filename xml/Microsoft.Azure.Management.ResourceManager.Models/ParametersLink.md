<Type Name="ParametersLink" FullName="Microsoft.Azure.Management.ResourceManager.Models.ParametersLink">
  <TypeSignature Language="C#" Value="public class ParametersLink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ParametersLink extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ParametersLink" />
  <TypeSignature Language="VB.NET" Value="Public Class ParametersLink" />
  <TypeSignature Language="F#" Value="type ParametersLink = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="130f9-101">展開パラメーターへの参照を表すエンティティです。</span><span class="sxs-lookup"><span data-stu-id="130f9-101">Entity representing the reference to the deployment paramaters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ParametersLink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ParametersLink.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="130f9-102">ParametersLink クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="130f9-102">Initializes a new instance of the ParametersLink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ParametersLink (string uri, string contentVersion = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string uri, string contentVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ParametersLink.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (uri As String, Optional contentVersion As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ParametersLink : string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ParametersLink" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ParametersLink (uri, contentVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="uri" Type="System.String" />
        <Parameter Name="contentVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="130f9-103">パラメーター ファイルの URI。</span><span class="sxs-lookup"><span data-stu-id="130f9-103">The URI of the parameters file.</span></span></param>
        <param name="contentVersion"><span data-ttu-id="130f9-104">含まれる場合は、テンプレート内の ContentVersion と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="130f9-104">If included, must match the ContentVersion in the template.</span></span></param>
        <summary>
            <span data-ttu-id="130f9-105">ParametersLink クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="130f9-105">Initializes a new instance of the ParametersLink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentVersion">
      <MemberSignature Language="C#" Value="public string ContentVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ParametersLink.ContentVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentVersion As String" />
      <MemberSignature Language="F#" Value="member this.ContentVersion : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ParametersLink.ContentVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="contentVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="130f9-106">取得または設定含まれている場合は、テンプレートの ContentVersion と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="130f9-106">Gets or sets if included, must match the ContentVersion in the template.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public string Uri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ParametersLink.Uri" />
      <MemberSignature Language="VB.NET" Value="Public Property Uri As String" />
      <MemberSignature Language="F#" Value="member this.Uri : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ParametersLink.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="130f9-107">取得またはパラメーター ファイルの URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="130f9-107">Gets or sets the URI of the parameters file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ParametersLink.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="parametersLink.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="130f9-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="130f9-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="130f9-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="130f9-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
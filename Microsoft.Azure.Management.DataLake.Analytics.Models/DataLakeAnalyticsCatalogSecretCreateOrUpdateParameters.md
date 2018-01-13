<Type Name="DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="25c94-101">Data Lake Analytics はカタログ シークレットの作成と更新プログラムのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="25c94-101">Data Lake Analytics catalog secret creation and update parameters.</span></span> <span data-ttu-id="25c94-102">これは廃止されており、次のリリースで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="25c94-102">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="25c94-103">DataLakeAnalyticsCatalogCredentialCreateOrUpdateParameters を使用してください。</span><span class="sxs-lookup"><span data-stu-id="25c94-103">Please use DataLakeAnalyticsCatalogCredentialCreateOrUpdateParameters instead.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="25c94-104">DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="25c94-104">Initializes a new instance of the DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters (string password, string uri = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string password, string uri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (password As String, Optional uri As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters : string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters (password, uri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="uri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="password"><span data-ttu-id="25c94-105">渡すシークレットのパスワード</span><span class="sxs-lookup"><span data-stu-id="25c94-105">the password for the secret to pass in</span></span></param>
        <param name="uri"><span data-ttu-id="25c94-106">形式で、シークレットの URI 識別子&lt;hostname&gt;:&lt;ポート&gt;</span><span class="sxs-lookup"><span data-stu-id="25c94-106">the URI identifier for the secret in the format &lt;hostname&gt;:&lt;port&gt;</span></span></param>
        <summary>
            <span data-ttu-id="25c94-107">DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="25c94-107">Initializes a new instance of the DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25c94-108">取得または設定を渡すシークレットのパスワード</span><span class="sxs-lookup"><span data-stu-id="25c94-108">Gets or sets the password for the secret to pass in</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public string Uri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters.Uri" />
      <MemberSignature Language="VB.NET" Value="Public Property Uri As String" />
      <MemberSignature Language="F#" Value="member this.Uri : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="25c94-109">形式で、シークレットの URI 識別子の設定を取得または&amp;lt; のホスト名&amp;gt;:&amp;lt; port&amp;gt;</span><span class="sxs-lookup"><span data-stu-id="25c94-109">Gets or sets the URI identifier for the secret in the format &amp;lt;hostname&amp;gt;:&amp;lt;port&amp;gt;</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataLakeAnalyticsCatalogSecretCreateOrUpdateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="25c94-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="25c94-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="25c94-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="25c94-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
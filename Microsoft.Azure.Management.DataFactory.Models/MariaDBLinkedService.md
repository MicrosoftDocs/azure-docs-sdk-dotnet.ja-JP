<Type Name="MariaDBLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.MariaDBLinkedService">
  <TypeSignature Language="C#" Value="public class MariaDBLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MariaDBLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.MariaDBLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class MariaDBLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type MariaDBLinkedService = class&#xA;    inherit LinkedService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.LinkedService</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("MariaDB")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9b23f-101">MariaDB サーバーにリンクされたサービスを指定します。</span><span class="sxs-lookup"><span data-stu-id="9b23f-101">MariaDB server linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MariaDBLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.MariaDBLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9b23f-102">MariaDBLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9b23f-102">Initializes a new instance of the MariaDBLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MariaDBLinkedService (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase connectionString = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, class Microsoft.Azure.Management.DataFactory.Models.SecretBase connectionString, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.MariaDBLinkedService.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional connectionString As SecretBase = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.MariaDBLinkedService : System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.MariaDBLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.MariaDBLinkedService (additionalProperties, connectVia, description, connectionString, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="connectionString" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="9b23f-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="9b23f-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="9b23f-104">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="9b23f-104">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="9b23f-105">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="9b23f-105">Linked service description.</span></span></param>
        <param name="connectionString"><span data-ttu-id="9b23f-106">ODBC 接続文字列。</span><span class="sxs-lookup"><span data-stu-id="9b23f-106">An ODBC connection string.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="9b23f-107">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="9b23f-107">The encrypted credential used for authentication.</span></span> <span data-ttu-id="9b23f-108">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="9b23f-108">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="9b23f-109">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="9b23f-109">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="9b23f-110">MariaDBLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9b23f-110">Initializes a new instance of the MariaDBLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.MariaDBLinkedService.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As SecretBase" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.MariaDBLinkedService.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.connectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9b23f-111">取得または ODBC 接続文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="9b23f-111">Gets or sets an ODBC connection string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.MariaDBLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.MariaDBLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.encryptedCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9b23f-112">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="9b23f-112">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="9b23f-113">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="9b23f-113">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="9b23f-114">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="9b23f-114">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.MariaDBLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="mariaDBLinkedService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9b23f-115">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="9b23f-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9b23f-116">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b23f-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
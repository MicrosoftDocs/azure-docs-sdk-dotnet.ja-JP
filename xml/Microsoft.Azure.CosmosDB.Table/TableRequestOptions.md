<Type Name="TableRequestOptions" FullName="Microsoft.Azure.CosmosDB.Table.TableRequestOptions">
  <TypeSignature Language="C#" Value="public sealed class TableRequestOptions : Microsoft.Azure.Storage.IRequestOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TableRequestOptions extends System.Object implements class Microsoft.Azure.Storage.IRequestOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableRequestOptions&#xA;Implements IRequestOptions" />
  <TypeSignature Language="F#" Value="type TableRequestOptions = class&#xA;    interface IRequestOptions" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Storage.IRequestOptions</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="ea78d-101">テーブル サービスに対する要求で指定できるタイムアウトと再試行のポリシーのオプションのセットを表します。</span><span class="sxs-lookup"><span data-stu-id="ea78d-101">Represents a set of timeout and retry policy options that may be specified for a request against the Table service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableRequestOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ea78d-102"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ea78d-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableRequestOptions (Microsoft.Azure.CosmosDB.Table.TableRequestOptions other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.#ctor(Microsoft.Azure.CosmosDB.Table.TableRequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (other As TableRequestOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.TableRequestOptions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions -&gt; Microsoft.Azure.CosmosDB.Table.TableRequestOptions" Usage="new Microsoft.Azure.CosmosDB.Table.TableRequestOptions other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="ea78d-103"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />の新しいインスタンスを初期化するために使用されるオブジェクト、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="ea78d-103">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object used to initialize a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> class.</span></span></param>
        <summary>
            <span data-ttu-id="ea78d-104"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> を指定して、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ea78d-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> class with the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableEncryptionPolicy EncryptionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.TableEncryptionPolicy EncryptionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.EncryptionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionPolicy As TableEncryptionPolicy" />
      <MemberSignature Language="F#" Value="member this.EncryptionPolicy : Microsoft.Azure.CosmosDB.Table.TableEncryptionPolicy with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.EncryptionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableEncryptionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea78d-105">取得または要求の暗号化ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="ea78d-105">Gets or sets the encryption policy for the request.</span></span>
            </summary>
        <value><span data-ttu-id="ea78d-106"><see cref="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.EncryptionPolicy" /> 型のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ea78d-106">An object of type <see cref="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.EncryptionPolicy" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionResolver">
      <MemberSignature Language="C#" Value="public Func&lt;string,string,string,bool&gt; EncryptionResolver { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`4&lt;string, string, string, bool&gt; EncryptionResolver" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.EncryptionResolver" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionResolver As Func(Of String, String, String, Boolean)" />
      <MemberSignature Language="F#" Value="member this.EncryptionResolver : Func&lt;string, string, string, bool&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.EncryptionResolver" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.String,System.String,System.String,System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea78d-107">取得または設定を示すかどうかは、プロパティを暗号化するか、パーティション キー、行キー、およびプロパティ名を指定する値を取得するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="ea78d-107">Gets or sets the delegate to get the value indicating whether or not a property should be encrypted, given the partition key, row key, and property name.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocationMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Storage.RetryPolicies.LocationMode&gt; LocationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Storage.RetryPolicies.LocationMode&gt; LocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.LocationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property LocationMode As Nullable(Of LocationMode)" />
      <MemberSignature Language="F#" Value="member this.LocationMode : Nullable&lt;Microsoft.Azure.Storage.RetryPolicies.LocationMode&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.LocationMode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Storage.IRequestOptions.LocationMode</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Storage.RetryPolicies.LocationMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea78d-108">取得または要求の配置モードを設定します。</span><span class="sxs-lookup"><span data-stu-id="ea78d-108">Gets or sets the location mode of the request.</span></span>
            </summary>
        <value><span data-ttu-id="ea78d-109">A<see cref="T:Microsoft.Azure.Storage.RetryPolicies.LocationMode" />要求の配置モードを示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="ea78d-109">A <see cref="T:Microsoft.Azure.Storage.RetryPolicies.LocationMode" /> enumeration value indicating the location mode of the request.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumExecutionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaximumExecutionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaximumExecutionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.MaximumExecutionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumExecutionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaximumExecutionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.MaximumExecutionTime" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Storage.IRequestOptions.MaximumExecutionTime</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea78d-110">取得または要求に対応するすべての潜在的な再試行の最大実行時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea78d-110">Gets or sets the maximum execution time for all potential retries for the request.</span></span>
            </summary>
        <value><span data-ttu-id="ea78d-111">A<see cref="T:System.TimeSpan" />要求の再試行の最大実行時間を表すです。</span><span class="sxs-lookup"><span data-stu-id="ea78d-111">A <see cref="T:System.TimeSpan" /> representing the maximum execution time for retries for the request.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PayloadFormat">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.CosmosDB.Table.TablePayloadFormat&gt; PayloadFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.CosmosDB.Table.TablePayloadFormat&gt; PayloadFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.PayloadFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property PayloadFormat As Nullable(Of TablePayloadFormat)" />
      <MemberSignature Language="F#" Value="member this.PayloadFormat : Nullable&lt;Microsoft.Azure.CosmosDB.Table.TablePayloadFormat&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.PayloadFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.CosmosDB.Table.TablePayloadFormat&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea78d-112">取得または設定、<see cref="T:Microsoft.Azure.CosmosDB.Table.TablePayloadFormat" />要求に対して使用されます。</span><span class="sxs-lookup"><span data-stu-id="ea78d-112">Gets or sets the <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePayloadFormat" /> that will be used for the request.</span></span>
            </summary>
        <value><span data-ttu-id="ea78d-113"><see cref="T:Microsoft.Azure.CosmosDB.Table.TablePayloadFormat" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="ea78d-113">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePayloadFormat" /> enumeration value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProjectSystemProperties">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ProjectSystemProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ProjectSystemProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.ProjectSystemProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property ProjectSystemProperties As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ProjectSystemProperties : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.ProjectSystemProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea78d-114">取得またはクエリにパーティション キーと行キーなどのシステム プロパティを含めるオプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="ea78d-114">Gets or sets the option to include system properties such as Partition Key and Row Key in queries.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyResolver">
      <MemberSignature Language="C#" Value="public Func&lt;string,string,string,string,Microsoft.Azure.CosmosDB.Table.EdmType&gt; PropertyResolver { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`5&lt;string, string, string, string, valuetype Microsoft.Azure.CosmosDB.Table.EdmType&gt; PropertyResolver" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.PropertyResolver" />
      <MemberSignature Language="VB.NET" Value="Public Property PropertyResolver As Func(Of String, String, String, String, EdmType)" />
      <MemberSignature Language="F#" Value="member this.PropertyResolver : Func&lt;string, string, string, string, Microsoft.Azure.CosmosDB.Table.EdmType&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.PropertyResolver" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.String,System.String,System.String,System.String,Microsoft.Azure.CosmosDB.Table.EdmType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea78d-115">取得または設定を取得するために使用するデリゲート、<see cref="T:Microsoft.Azure.CosmosDB.Table.EdmType" />エンティティのプロパティに、パーティション キー、行キー、およびプロパティ名を指定します。</span><span class="sxs-lookup"><span data-stu-id="ea78d-115">Gets or sets the delegate that is used to get the <see cref="T:Microsoft.Azure.CosmosDB.Table.EdmType" /> for an entity property given the partition key, row key, and the property name.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireEncryption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequireEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequireEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.RequireEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireEncryption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequireEncryption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.RequireEncryption" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Storage.IRequestOptions.RequireEncryption</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea78d-116">取得またはクライアント ライブラリによって読み取りし、書き込みのデータを暗号化するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea78d-116">Gets or sets a value to indicate whether data written and read by the client library should be encrypted.</span></span>
            </summary>
        <value><span data-ttu-id="ea78d-117">使用して<c>true</c>すべてのトランザクションの暗号化/暗号化解除、それ以外のデータがする必要がありますを指定する<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="ea78d-117">Use <c>true</c> to specify that data should be encrypted/decrypted for all transactions; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Storage.RetryPolicies.IRetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Storage.RetryPolicies.IRetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As IRetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.Azure.Storage.RetryPolicies.IRetryPolicy with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.RetryPolicy" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Storage.IRequestOptions.RetryPolicy</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.RetryPolicies.IRetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea78d-118">取得または要求の再試行ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="ea78d-118">Gets or sets the retry policy for the request.</span></span>
            </summary>
        <value><span data-ttu-id="ea78d-119"><see cref="T:Microsoft.Azure.Storage.RetryPolicies.IRetryPolicy" /> 型のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ea78d-119">An object of type <see cref="T:Microsoft.Azure.Storage.RetryPolicies.IRetryPolicy" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ServerTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ServerTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.ServerTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ServerTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.ServerTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Storage.IRequestOptions.ServerTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea78d-120">取得または、サーバーに要求のタイムアウト間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea78d-120">Gets or sets the server timeout interval for the request.</span></span>
            </summary>
        <value><span data-ttu-id="ea78d-121">A<see cref="T:System.TimeSpan" />の要求に対するサーバー タイムアウト間隔を表すです。</span><span class="sxs-lookup"><span data-stu-id="ea78d-121">A <see cref="T:System.TimeSpan" /> containing the server timeout interval for the request.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.SessionToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea78d-122">取得または Azure Cosmos DB サービス内のセッションの整合性に使用するためのトークンを設定します。</span><span class="sxs-lookup"><span data-stu-id="ea78d-122">Gets or sets the token for use with session consistency in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="ea78d-123">セッションで使用するためのトークンです。</span><span class="sxs-lookup"><span data-stu-id="ea78d-123">The token for use with session consistency.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="ea78d-124">1 つ、 <see cref="T:Microsoft.Azure.CosmosDB.ConsistencyLevel" /> Azure Cosmos DB は、セッションのです。</span><span class="sxs-lookup"><span data-stu-id="ea78d-124">One of the <see cref="T:Microsoft.Azure.CosmosDB.ConsistencyLevel" /> for Azure Cosmos DB is Session.</span></span>  
            <span data-ttu-id="ea78d-125"><para>セッションの整合性を使用するときに、Azure Cosmos DB への新しい各書き込み要求には新しい SessionToken が割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="ea78d-125"><para> When working with Session consistency, each new write request to Azure Cosmos DB is assigned a new SessionToken.</span></span>
            <span data-ttu-id="ea78d-126"><see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />はこのトークンを使用して内部的に読み取り/クエリ要求ごとに整合性レベルの設定が維持されるようにします。</span><span class="sxs-lookup"><span data-stu-id="ea78d-126">The <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> will use this token internally with each read/query request to ensure that the set consistency level is maintained.</span></span>
            
             <span data-ttu-id="ea78d-127"><para>一部のシナリオでは、考えてください。 このセッションを管理する必要があります。たとえば web アプリケーションは、複数のノード、各ノードが、それぞれのインスタンスの<see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />場合に、同じセッションに参加するこれらのノード (できるように、独自の書き込み一貫して全体で読み取る web 層)、SessionToken を送信する必要がありますクライアント層のノードを 1 つの書き込みアクションのいずれかで、cookie、またはその他の機構を使用していて、web 層にそのトークンのフローの後続の読み取り。</span><span class="sxs-lookup"><span data-stu-id="ea78d-127"><para> In some scenarios you need to manage this Session yourself; Consider a web application with multiple nodes, each node will have its own instance of <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> If you wanted these nodes to participate in the same session (to be able read your own writes consistently across web tiers) you would have to send the SessionToken from one of the write action on one node to the client tier, using a cookie or some other mechanism, and have that token flow back to the web tier for subsequent reads.</span></span>
            <span data-ttu-id="ea78d-128">これは、Azure ロード バランサーなどの要求間でセッション アフィニティが維持されないラウンド ロビンのロード バランサーを使用している場合</span><span class="sxs-lookup"><span data-stu-id="ea78d-128">If you are using a round-robin load balancer which does not maintain session affinity between requests, such as the Azure Load Balancer,</span></span>  
            <span data-ttu-id="ea78d-129">読み取りでした可能性があります。 そこで別のノードで、書き込み要求をセッションが作成されました。</span><span class="sxs-lookup"><span data-stu-id="ea78d-129">the read could potentially land on a different node to the write request, where the session was created.</span></span> 
            <span data-ttu-id="ea78d-130"></para><para>前述のように、Azure Cosmos DB SessionToken 間をフローしない場合を終了して、読み取りの一貫性のない結果を時間の期間。</para></para></span><span class="sxs-lookup"><span data-stu-id="ea78d-130"></para><para> If you do not flow the Azure Cosmos DB SessionToken across as described above you could end up with inconsistent read results for a period of time. </para></para></span></span></remarks>
        <altmember cref="T:Microsoft.Azure.CosmosDB.ConsistencyLevel" />
      </Docs>
    </Member>
  </Members>
</Type>
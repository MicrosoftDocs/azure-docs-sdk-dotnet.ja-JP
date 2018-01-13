<Type Name="SearchService" FullName="Microsoft.Azure.Management.Search.Models.SearchService">
  <TypeSignature Language="C#" Value="public class SearchService : Microsoft.Azure.Management.Search.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchService extends Microsoft.Azure.Management.Search.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.Models.SearchService" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchService&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type SearchService = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Search.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure Search サービスとその現在の状態について説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.SearchService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SearchService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchService (string location, Microsoft.Azure.Management.Search.Models.Sku sku, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;int&gt; replicaCount = null, Nullable&lt;int&gt; partitionCount = null, Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt; hostingMode = null, Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; status = null, string statusDetails = null, Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class Microsoft.Azure.Management.Search.Models.Sku sku, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;int32&gt; replicaCount, valuetype System.Nullable`1&lt;int32&gt; partitionCount, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.HostingMode&gt; hostingMode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; status, string statusDetails, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.SearchService.#ctor(System.String,Microsoft.Azure.Management.Search.Models.Sku,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.Search.Models.HostingMode},System.Nullable{Microsoft.Azure.Management.Search.Models.SearchServiceStatus},System.String,System.Nullable{Microsoft.Azure.Management.Search.Models.ProvisioningState})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Search.Models.SearchService : string * Microsoft.Azure.Management.Search.Models.Sku * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt; * Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; * string * Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; -&gt; Microsoft.Azure.Management.Search.Models.SearchService" Usage="new Microsoft.Azure.Management.Search.Models.SearchService (location, sku, id, name, type, tags, replicaCount, partitionCount, hostingMode, status, statusDetails, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Search.Models.Sku" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="replicaCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="partitionCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="hostingMode" Type="System.Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt;" />
        <Parameter Name="statusDetails" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt;" />
      </Parameters>
      <Docs>
        <param name="location">リソースの地理的な場所です。
            サポートされており、登録済みの Azure の Geo リージョンは (たとえば、米国西部、米国東部、東南アジアなど) の 1 つがあります。</param>
        <param name="sku">SKU を決定する検索サービスの価格レベルと容量の制限。</param>
        <param name="id">リソースの ID。 これは、使用できます、Azure リソース マネージャーにリソースを相互にリンクします。</param>
        <param name="name">リソースの名前。</param>
        <param name="type">リソースの種類。</param>
        <param name="tags">Azure ポータルでリソースを分類するためにタグを付けます。</param>
        <param name="replicaCount">Search サービス内のレプリカの数。 指定した場合は、1 から 12 standard Sku の間、または 1 ~ 3 の基本的な SKU の包括的で値を指定してする必要があります。</param>
        <param name="partitionCount">検索サービスのパーティションの数指定した場合は、1、2、3、4、6、または 12 にできます。
            1 より大きい値では、標準 Sku 有効のみです。 HostingMode 'highDensity' éý 'standard3' サービスの有効な値は 1 ~ 3 の範囲です。</param>
        <param name="hostingMode">Standard3 SKU にのみ適用できます。
            他の任意の SKU で許可される最大のインデックスよりも多くは最大で 1,000 個のインデックスを許可する最大 3 つの高密度パーティションを有効にするには、このプロパティを設定することができます。 Standard3 SKU 値は 'default' または 'highDensity' のいずれかです。
            その他のすべての Sku では、この値は 'default' をする必要があります。 使用可能な値が含まれます: 'default'、'highDensity'</param>
        <param name="status">検索サービスの状態。 使用可能な値が含まれます: '実行中: Search サービスが実行されていると、プロビジョニング操作がない進行中です。 'プロビジョニング': Search サービスが中プロビジョニングまたは拡大または縮小します。 '削除': Search サービスが削除されています。 '低下': Search サービスが低下します。 これは、基になる検索単位が異常な場合に発生します。 Search サービスは、運用上のほとんどの場合ですがパフォーマンスが低下する可能性があり、いくつかの要求が削除される可能性があります。 'disabled': Search サービスを無効にします。 この状態では、サービスはすべての API 要求を拒否します。 'error': Search サービスが、エラー状態にします。 サービスを低下、無効な場合、またはエラーを示している場合は、Azure Search チームが、基になる問題を積極的に調査を意味します。
            この状態の専用サービスは、プロビジョニングされた検索単位数に基づいて、引き続き課金対象になります。 使用可能な値が含まれます: 'を実行している'、'プロビジョニング、' 'を削除する'、'低下'、'disabled'、'error'</param>
        <param name="statusDetails">検索サービスの状態の詳細。</param>
        <param name="provisioningState">最後のプロビジョニング操作の状態は、Search サービスで実行します。 プロビジョニングは、サービスの容量が確立されるときに発生する中間的な状態です。 容量がセットアップされたら、provisioningState は、'成功' または '失敗' に変更します。 クライアント アプリケーションを使用して、検索サービスの取得操作を操作が完了したタイミングを参照してください (推奨されるポーリング間隔は 30 秒から 1 分間) のプロビジョニング ステータスをポーリングできます。 無料のサービスを使用している場合、この値を検索の作成サービスへの呼び出しで直接には、'成功' として返される傾向があります。 これは、無料のサービスは既にセットアップされている容量を使用するためです。 使用可能な値が含まれます: は ' succeeded'、'プロビジョニング'、'失敗'</param>
        <summary>
            SearchService クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt; HostingMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.HostingMode&gt; HostingMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.HostingMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingMode As Nullable(Of HostingMode)" />
      <MemberSignature Language="F#" Value="member this.HostingMode : Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt; with get, set" Usage="Microsoft.Azure.Management.Search.Models.SearchService.HostingMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または standard3 SKU に対してのみ該当する設定。 他の任意の SKU で許可される最大のインデックスよりも多くは最大で 1,000 個のインデックスを許可する最大 3 つの高密度パーティションを有効にするには、このプロパティを設定することができます。 Standard3 SKU 値は 'default' または 'highDensity' のいずれかです。 その他のすべての Sku では、この値は 'default' をする必要があります。 使用可能な値が含まれます: 'default'、'highDensity'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PartitionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PartitionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.PartitionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PartitionCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Search.Models.SearchService.PartitionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partitionCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または検索サービスのパーティションの数を設定指定した場合は、1、2、3、4、6、または 12 にできます。 1 より大きい値では、標準 Sku 有効のみです。 HostingMode 'highDensity' éý 'standard3' サービスの有効な値は 1 ~ 3 の範囲です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.Search.Models.SearchService.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Search サービスで実行される操作のプロビジョニング、最後の状態を取得します。 プロビジョニングは、サービスの容量が確立されるときに発生する中間的な状態です。 容量がセットアップされたら、provisioningState は、'成功' または '失敗' に変更します。 クライアント アプリケーションを使用して、検索サービスの取得操作を操作が完了したタイミングを参照してください (推奨されるポーリング間隔は 30 秒から 1 分間) のプロビジョニング ステータスをポーリングできます。 無料のサービスを使用している場合、この値を検索の作成サービスへの呼び出しで直接には、'成功' として返される傾向があります。 これは、無料のサービスは既にセットアップされている容量を使用するためです。 使用可能な値が含まれます: は ' succeeded'、'プロビジョニング'、'失敗'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ReplicaCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ReplicaCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.ReplicaCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicaCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ReplicaCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Search.Models.SearchService.ReplicaCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.replicaCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Search サービスのレプリカの数を設定します。 指定した場合は、1 から 12 standard Sku の間、または 1 ~ 3 の基本的な SKU の包括的で値を指定してする必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Search.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Search.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Search.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Search.Models.SearchService.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を決定する検索サービスの SKU の価格レベルと容量の制限。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of SearchServiceStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt;" Usage="Microsoft.Azure.Management.Search.Models.SearchService.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            検索サービスの状態を取得します。 使用可能な値が含まれます: '実行中: Search サービスが実行されていると、プロビジョニング操作がない進行中です。 'プロビジョニング': Search サービスが中プロビジョニングまたは拡大または縮小します。 '削除': Search サービスが削除されています。 '低下': Search サービスが低下します。 これは、基になる検索単位が異常な場合に発生します。 Search サービスは、運用上のほとんどの場合ですがパフォーマンスが低下する可能性があり、いくつかの要求が削除される可能性があります。
            'disabled': Search サービスを無効にします。 この状態では、サービスはすべての API 要求を拒否します。 'error': Search サービスが、エラー状態にします。 サービスを低下、無効な場合、またはエラーを示している場合は、Azure Search チームが、基になる問題を積極的に調査を意味します。 この状態の専用サービスは、プロビジョニングされた検索単位数に基づいて、引き続き課金対象になります。 使用可能な値が含まれます: 'を実行している'、'プロビジョニング、' 'を削除する'、'低下'、'disabled'、'error'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusDetails">
      <MemberSignature Language="C#" Value="public string StatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.StatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.StatusDetails : string" Usage="Microsoft.Azure.Management.Search.Models.SearchService.StatusDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.statusDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            検索サービスの状態の詳細を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.SearchService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="searchService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
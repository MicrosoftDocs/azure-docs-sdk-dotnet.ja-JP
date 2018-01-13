<Type Name="ServiceDescription" FullName="System.Fabric.Description.ServiceDescription">
  <TypeSignature Language="C#" Value="public abstract class ServiceDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceDescription" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceDescription" />
  <TypeSignature Language="F#" Value="type ServiceDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.StatelessServiceDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.StatefulServiceDescription))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para> な ServiceDescription には、すべてのサービスを作成するために必要な情報が含まれます。 </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ServiceDescription (System.Fabric.Description.ServiceDescription other);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.Description.ServiceDescription other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceDescription.#ctor(System.Fabric.Description.ServiceDescription)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (other As ServiceDescription)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceDescription : System.Fabric.Description.ServiceDescription -&gt; System.Fabric.Description.ServiceDescription" Usage="new System.Fabric.Description.ServiceDescription other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.Description.ServiceDescription" />
      </Parameters>
      <Docs>
        <param name="other">
          <para>パラメーターのコピー元となるサービスの説明。</para>
        </param>
        <summary>
          <para>
            インスタンスを作成、<see cref="T:System.Fabric.Description.ServiceDescription" />から別のパラメーターを持つクラス<see cref="T:System.Fabric.Description.ServiceDescription" />オブジェクト。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ServiceDescription (System.Fabric.Description.ServiceDescriptionKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Description.ServiceDescriptionKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceDescription.#ctor(System.Fabric.Description.ServiceDescriptionKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (kind As ServiceDescriptionKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceDescription : System.Fabric.Description.ServiceDescriptionKind -&gt; System.Fabric.Description.ServiceDescription" Usage="new System.Fabric.Description.ServiceDescription kind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="System.Fabric.Description.ServiceDescriptionKind" />
      </Parameters>
      <Docs>
        <param name="kind">
          <para>サービスの種類について説明します。</para>
        </param>
        <summary>
          <para>インスタンスを初期化<see cref="T:System.Fabric.Description.ServiceDescription" />サービスの種類を使用します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri with get, set" Usage="System.Fabric.Description.ServiceDescription.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはアプリケーションの URI を設定します。</para>
        </summary>
        <value>
          <para>アプリケーション名。</para>
        </value>
        <remarks>
          <para>アプリケーションの一意の名前は、これはグループ サービスを一緒に管理用に使用します。 スキームである必要があります"fabric:/"アプリケーション名は、サービス名のプレフィックスをする必要があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Correlations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceCorrelationDescription&gt; Correlations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ServiceCorrelationDescription&gt; Correlations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.Correlations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Correlations As IList(Of ServiceCorrelationDescription)" />
      <MemberSignature Language="F#" Value="member this.Correlations : System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceCorrelationDescription&gt;" Usage="System.Fabric.Description.ServiceDescription.Correlations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceCorrelationDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            一覧を取得<see cref="T:System.Fabric.Description.ServiceCorrelationDescription" />他のサービスとこのサービスの相関関係を記述します。
            </para>
        </summary>
        <value>
          <para>相関関係の説明の一覧を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMoveCost">
      <MemberSignature Language="C#" Value="public System.Fabric.MoveCost DefaultMoveCost { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.MoveCost DefaultMoveCost" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.DefaultMoveCost" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMoveCost As MoveCost" />
      <MemberSignature Language="F#" Value="member this.DefaultMoveCost : System.Fabric.MoveCost with get, set" Usage="System.Fabric.Description.ServiceDescription.DefaultMoveCost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.MoveCost</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> 
            既定値の設定を取得または<see cref="T:System.Fabric.MoveCost" />サービスの値。
            </para>
        </summary>
        <value>
          <para> 既定値<see cref="T:System.Fabric.MoveCost" />サービス用設定される値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializationData">
      <MemberSignature Language="C#" Value="public byte[] InitializationData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] InitializationData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.InitializationData" />
      <MemberSignature Language="VB.NET" Value="Public Property InitializationData As Byte()" />
      <MemberSignature Language="F#" Value="member this.InitializationData : byte[] with get, set" Usage="System.Fabric.Description.ServiceDescription.InitializationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または作成するときは、渡される初期化データをサービス インスタンスまたはレプリカに設定します。</para>
        </summary>
        <value>
          <para>初期化データを返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDefaultMoveCostSpecified">
      <MemberSignature Language="C#" Value="public bool IsDefaultMoveCostSpecified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDefaultMoveCostSpecified" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.IsDefaultMoveCostSpecified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDefaultMoveCostSpecified As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDefaultMoveCostSpecified : bool" Usage="System.Fabric.Description.ServiceDescription.IsDefaultMoveCostSpecified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> 
            かどうか、既定値を取得<see cref="T:System.Fabric.MoveCost" />サービスが指定されています。
            </para>
        </summary>
        <value>
          <para>示すフラグかどうか、既定値<see cref="T:System.Fabric.MoveCost" />サービスが指定されています。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServiceDescriptionKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServiceDescriptionKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As ServiceDescriptionKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.Description.ServiceDescriptionKind" Usage="System.Fabric.Description.ServiceDescription.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceDescriptionKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>このサービスのサービスの種類 (たとえば、ステートフルなまたはステートレス) を取得します。</para>
        </summary>
        <value>
          <para>サービスの種類。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.ServiceLoadMetricDescription&gt; Metrics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.ServiceLoadMetricDescription&gt; Metrics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public Property Metrics As KeyedCollection(Of String, ServiceLoadMetricDescription)" />
      <MemberSignature Language="F#" Value="member this.Metrics : System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceLoadMetricDescription&gt; with get, set" Usage="System.Fabric.Description.ServiceDescription.Metrics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.KeyedCollection&lt;System.String,System.Fabric.Description.ServiceLoadMetricDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            キー付きコレクションの取得または設定<see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" />s このサービスに対して定義されている負荷メトリックを記述します。
            </para>
        </summary>
        <value>
          <para>一連の負荷メトリックの説明を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionSchemeDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.PartitionSchemeDescription PartitionSchemeDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.PartitionSchemeDescription PartitionSchemeDescription" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.PartitionSchemeDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionSchemeDescription As PartitionSchemeDescription" />
      <MemberSignature Language="F#" Value="member this.PartitionSchemeDescription : System.Fabric.Description.PartitionSchemeDescription with get, set" Usage="System.Fabric.Description.ServiceDescription.PartitionSchemeDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.PartitionSchemeDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはこのサービスに使用するパーティション スキームの説明を設定します。</para>
        </summary>
        <value>
          <para>サービスに使用するパーティション構成です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlacementConstraints">
      <MemberSignature Language="C#" Value="public string PlacementConstraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PlacementConstraints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.PlacementConstraints" />
      <MemberSignature Language="VB.NET" Value="Public Property PlacementConstraints As String" />
      <MemberSignature Language="F#" Value="member this.PlacementConstraints : string with get, set" Usage="System.Fabric.Description.ServiceDescription.PlacementConstraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> 取得またはこのサービスの配置に関する制約を設定します。</para>
        </summary>
        <value>
          <para> 配置に関する制約を返します。</para>
        </value>
        <remarks>
          <para>配置に関する制約は、サービスを特定のノード プロパティ (およびそれらのプロパティの値) は、配置を制御するために選択できるようにするブール型のステートメントです。  ノードのプロパティは、通常、ノードのハードウェア機能に関連して、ノードに関するいくつか追加のメタデータを定義するキー値のペアです。  ノードのプロパティとして公開される可能性がハードウェアの特性には、"HasDisk"、"%memorysize"、"StorageSize"、"NumberOfCores"などがあります。サービスを展開するときに、管理者は、サービスに配慮してプロパティに加え、これらのプロパティの値の要件を定義する簡単なブール演算子を定義できます。  例: (HasDisk = = true &amp; &amp; %memorysize&gt;= 2048)。  実行時に Service Fabric 負荷分散はのみサービスに配置をサービスに必要なものと一致する値を持つプロパティを持つノード。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PlacementPolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ServicePlacementPolicyDescription&gt; PlacementPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ServicePlacementPolicyDescription&gt; PlacementPolicies" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.PlacementPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PlacementPolicies As IList(Of ServicePlacementPolicyDescription)" />
      <MemberSignature Language="F#" Value="member this.PlacementPolicies : System.Collections.Generic.IList&lt;System.Fabric.Description.ServicePlacementPolicyDescription&gt;" Usage="System.Fabric.Description.ServiceDescription.PlacementPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.ServicePlacementPolicyDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> 
            一覧を取得<see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" />をこのサービスの配置ポリシーをについて説明します。
            </para>
        </summary>
        <value>
          <para>配置ポリシーの説明の一覧を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceDnsName">
      <MemberSignature Language="C#" Value="public string ServiceDnsName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceDnsName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.ServiceDnsName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceDnsName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceDnsName : string with get, set" Usage="System.Fabric.Description.ServiceDescription.ServiceDnsName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            取得またはサービスの DNS 名を設定します。 これを指定するとかどうか、サービスの代わりに DNS 名を介してアクセスできる<see cref="P:System.Fabric.Description.ServiceDescription.ServiceName" />です。
            </para>
        </summary>
        <value>
          <para>サービスの DNS 名または<c>null</c>サービスは、指定した DNS 名を持っていない場合。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri with get, set" Usage="System.Fabric.Description.ServiceDescription.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはこのサービスの URI を設定します。</para>
        </summary>
        <value>
          <para>サービスの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationMode">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServicePackageActivationMode ServicePackageActivationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServicePackageActivationMode ServicePackageActivationMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.ServicePackageActivationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePackageActivationMode As ServicePackageActivationMode" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationMode : System.Fabric.Description.ServicePackageActivationMode with get, set" Usage="System.Fabric.Description.ServiceDescription.ServicePackageActivationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePackageActivationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> 
            取得または設定、<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービス。
            </para>
        </summary>
        <value>
          <para> 
            A<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />を含むサービス パッケージのライセンス認証モードを表す列挙体、<see cref="P:System.Fabric.Description.ServiceDescription.ServiceTypeName" />がアクティブになるレプリカは、これによって説明されるサービスのインスタンスをホストして<see cref="T:System.Fabric.Description.ServiceDescription" />オブジェクト。 参照してください<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />詳細についてはします。
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string with get, set" Usage="System.Fabric.Description.ServiceDescription.ServiceTypeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはサービス型の名前を設定します。</para>
        </summary>
        <value>
          <para>サービスの種類の名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
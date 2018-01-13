<Type Name="IRecommendedElasticPool" FullName="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool">
  <TypeSignature Language="C#" Value="public interface IRecommendedElasticPool : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRecommendedElasticPool implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRecommendedElasticPool&#xA;Implements IHasId, IHasInner(Of RecommendedElasticPoolInner), IHasManager(Of ISqlManager), IHasName, IHasResourceGroup, IRefreshable(Of IRecommendedElasticPool)" />
  <TypeSignature Language="F#" Value="type IRecommendedElasticPool = interface&#xA;    interface IRefreshable&lt;IRecommendedElasticPool&gt;&#xA;    interface IHasInner&lt;RecommendedElasticPoolInner&gt;&#xA;    interface IHasResourceGroup&#xA;    interface IHasName&#xA;    interface IHasId&#xA;    interface IHasManager&lt;ISqlManager&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Azure SQL の推奨 ElasticPool の変更できないクライアント側表現。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DatabaseDtuMax">
      <MemberSignature Language="C#" Value="public double DatabaseDtuMax { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DatabaseDtuMax" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.DatabaseDtuMax" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseDtuMax As Double" />
      <MemberSignature Language="F#" Value="member this.DatabaseDtuMax : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.DatabaseDtuMax" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            データベースの最大の DTU を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseDtuMin">
      <MemberSignature Language="C#" Value="public double DatabaseDtuMin { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 DatabaseDtuMin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.DatabaseDtuMin" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseDtuMin As Double" />
      <MemberSignature Language="F#" Value="member this.DatabaseDtuMin : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.DatabaseDtuMin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            データベースの DTU の最小値を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseEdition">
      <MemberSignature Language="C#" Value="public string DatabaseEdition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseEdition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.DatabaseEdition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseEdition As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseEdition : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.DatabaseEdition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure SQL 推奨弾力性プールのエディションを取得します。 ElasticPoolEditions 列挙には、有効なすべてのエディションが含まれています。
            使用可能な値が含まれます: 'Basic'、'Standard'、'Premium' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Databases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; Databases { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; Databases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.Databases" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Databases As IReadOnlyList(Of ISqlDatabase)" />
      <MemberSignature Language="F#" Value="member this.Databases : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.Databases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このプール内には、Azure SQL データベースの一覧を取得します。 展開されたプロパティです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dtu">
      <MemberSignature Language="C#" Value="public double Dtu { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Dtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.Dtu" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Dtu As Double" />
      <MemberSignature Language="F#" Value="member this.Dtu : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.Dtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得 SQL Azure の DTU は、弾力性プールをお勧めします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatabase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase GetDatabase (string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase GetDatabase(string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.GetDatabase(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDatabase (databaseName As String) As ISqlDatabase" />
      <MemberSignature Language="F#" Value="abstract member GetDatabase : string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase" Usage="iRecommendedElasticPool.GetDatabase databaseName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseName">取得するデータベースの名前。</param>
        <summary>
            推奨されるデータベース内の特定のデータベースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>推奨されているデータベースについては、弾力性プールをお勧めします。</return>
      </Docs>
    </Member>
    <Member MemberName="ListDatabases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; ListDatabases ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; ListDatabases() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.ListDatabases" />
      <MemberSignature Language="VB.NET" Value="Public Function ListDatabases () As IReadOnlyList(Of ISqlDatabase)" />
      <MemberSignature Language="F#" Value="abstract member ListDatabases : unit -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;" Usage="iRecommendedElasticPool.ListDatabases " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Azure への呼び出しをすることにより、データベースの一覧をフェッチします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>推奨エラスティック プール内のデータベースの一覧です。</return>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolMetric&gt; ListMetrics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolMetric&gt; ListMetrics() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.ListMetrics" />
      <MemberSignature Language="VB.NET" Value="Public Function ListMetrics () As IReadOnlyList(Of IRecommendedElasticPoolMetric)" />
      <MemberSignature Language="F#" Value="abstract member ListMetrics : unit -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolMetric&gt;" Usage="iRecommendedElasticPool.ListMetrics " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Azure への呼び出しをすることで、メトリック情報の一覧をフェッチします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>推奨エラスティック プール内のデータベースの一覧です。</return>
      </Docs>
    </Member>
    <Member MemberName="MaxObservedDtu">
      <MemberSignature Language="C#" Value="public double MaxObservedDtu { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 MaxObservedDtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.MaxObservedDtu" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxObservedDtu As Double" />
      <MemberSignature Language="F#" Value="member this.MaxObservedDtu : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.MaxObservedDtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            観察された最大の DTU を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxObservedStorageMB">
      <MemberSignature Language="C#" Value="public double MaxObservedStorageMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 MaxObservedStorageMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.MaxObservedStorageMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxObservedStorageMB As Double" />
      <MemberSignature Language="F#" Value="member this.MaxObservedStorageMB : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.MaxObservedStorageMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メガバイト単位で観察された最大のストレージを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObservationPeriodEnd">
      <MemberSignature Language="C#" Value="public DateTime ObservationPeriodEnd { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ObservationPeriodEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.ObservationPeriodEnd" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ObservationPeriodEnd As DateTime" />
      <MemberSignature Language="F#" Value="member this.ObservationPeriodEnd : DateTime" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.ObservationPeriodEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            監視期間の開始 (ISO8601 形式) を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObservationPeriodStart">
      <MemberSignature Language="C#" Value="public DateTime ObservationPeriodStart { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ObservationPeriodStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.ObservationPeriodStart" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ObservationPeriodStart As DateTime" />
      <MemberSignature Language="F#" Value="member this.ObservationPeriodStart : DateTime" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.ObservationPeriodStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            監視期間の開始 (ISO8601 形式) を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerName">
      <MemberSignature Language="C#" Value="public string SqlServerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.SqlServerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlServerName As String" />
      <MemberSignature Language="F#" Value="member this.SqlServerName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.SqlServerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このデータベースが属する SQL Server の名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageMB">
      <MemberSignature Language="C#" Value="public double StorageMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 StorageMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.StorageMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageMB As Double" />
      <MemberSignature Language="F#" Value="member this.StorageMB : double" Usage="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPool.StorageMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            記憶域のサイズをメガバイト単位で取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
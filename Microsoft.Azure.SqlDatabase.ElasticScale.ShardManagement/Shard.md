<Type Name="Shard" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard">
  <TypeSignature Language="C#" Value="public sealed class Shard : IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Shard extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Shard&#xA;Implements IEquatable(Of Shard)" />
  <TypeSignature Language="F#" Value="type Shard = class&#xA;    interface IShardProvider&lt;ShardLocation&gt;&#xA;    interface IShardProvider&#xA;    interface ICloneable&lt;Shard&gt;&#xA;    interface IEquatable&lt;Shard&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            単一のシャードの表現。 シャードは、基本的にデータ ソース ロケーターつまり<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />シャードのマップに登録されています。 シャードは、マッピングのターゲットとしてマッピングで使用されます (を参照してください<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1" />と<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1" />)。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Shard" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&#xA;override this.Clone : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" Usage="shard.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ICloneable`1.Clone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            インスタンスを複製します。
            </summary>
        <returns>インスタンスのクローンを作成します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.Equals(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Shard) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard -&gt; bool" Usage="shard.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
      </Parameters>
      <Docs>
        <param name="other">比較するシャードです。</param>
        <summary>
            等値比較を実行のシャードを指定します。
            </summary>
        <returns>このオブジェクトは、それ以外の場合は false、他のオブジェクトと等しい場合は true。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="shard.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">現在のオブジェクトと比較するオブジェクト。</param>
        <summary>
            指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。
            </summary>
        <returns>指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="shard.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            このインスタンスのハッシュ コードを計算します。
            </summary>
        <returns>オブジェクトのハッシュ コード。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As ShardLocation" />
      <MemberSignature Language="F#" Value="member this.Location : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            シャードの場所を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnection">
      <MemberSignature Language="C#" Value="public System.Data.SqlClient.SqlConnection OpenConnection (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.SqlClient.SqlConnection OpenConnection(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.OpenConnection(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnection (connectionString As String) As SqlConnection" />
      <MemberSignature Language="F#" Value="member this.OpenConnection : string -&gt; System.Data.SqlClient.SqlConnection" Usage="shard.OpenConnection connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.SqlClient.SqlConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">
            SQL Server 資格情報または統合セキュリティの設定などの資格情報で接続文字列です。 サーバーと、データベース、シャードの名前のホスト名は、キーの参照操作から取得されます。
            </param>
        <summary>
            開き、通常<see cref="T:System.Data.SqlClient.SqlConnection" />指定のシャードと<see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />です。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            なお、<see cref="T:System.Data.SqlClient.SqlConnection" />この呼び出しによって返されるオブジェクトが一時的なエラーから保護されていません。 呼び出し元は、transient fault handling Microsoft Patterns and Practices チームからの Enterprise Library の機能を使用して、アプリケーション コードで、たとえば、一時的なエラーへの接続を保護するベスト プラクティスに従う必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnection">
      <MemberSignature Language="C#" Value="public System.Data.SqlClient.SqlConnection OpenConnection (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.SqlClient.SqlConnection OpenConnection(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.OpenConnection(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnection (connectionString As String, options As ConnectionOptions) As SqlConnection" />
      <MemberSignature Language="F#" Value="member this.OpenConnection : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions -&gt; System.Data.SqlClient.SqlConnection" Usage="shard.OpenConnection (connectionString, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.SqlClient.SqlConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions" />
      </Parameters>
      <Docs>
        <param name="connectionString">
            SQL Server 資格情報または統合セキュリティの設定などの資格情報で接続文字列です。 サーバーと、データベース、シャードの名前のホスト名は、キーの参照操作から取得されます。
            </param>
        <param name="options">検証操作で実行するためのオプションには、接続が開かれます。</param>
        <summary>
            開き、通常<see cref="T:System.Data.SqlClient.SqlConnection" />指定のシャードにします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            なお、<see cref="T:System.Data.SqlClient.SqlConnection" />この呼び出しによって返されるオブジェクトが一時的なエラーから保護されていません。 呼び出し元は、transient fault handling Microsoft Patterns and Practices チームからの Enterprise Library の機能を使用して、アプリケーション コードで、たとえば、一時的なエラーへの接続を保護するベスト プラクティスに従う必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt; OpenConnectionAsync (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.SqlClient.SqlConnection&gt; OpenConnectionAsync(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.OpenConnectionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionAsync (connectionString As String) As Task(Of SqlConnection)" />
      <MemberSignature Language="F#" Value="member this.OpenConnectionAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;" Usage="shard.OpenConnectionAsync connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">
            SQL Server 資格情報または統合セキュリティの設定などの資格情報で接続文字列です。 サーバーと、データベース、シャードの名前のホスト名は、キーの参照操作から取得されます。
            </param>
        <summary>
            非同期的に開き、通常<see cref="T:System.Data.SqlClient.SqlConnection" />指定のシャードと<see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />です。
            </summary>
        <returns>開かれた SqlConnection をカプセル化タスク</returns>
        <remarks>
            なお、<see cref="T:System.Data.SqlClient.SqlConnection" />この呼び出しによって返されるオブジェクトが一時的なエラーから保護されていません。 呼び出し元は、transient fault handling Microsoft Patterns and Practices チームからの Enterprise Library の機能を使用して、アプリケーション コードで、たとえば、一時的なエラーへの接続を保護するベスト プラクティスに従う必要があります。
            使用状況以外のすべてのエラーは返されたタスクによって伝達されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt; OpenConnectionAsync (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.SqlClient.SqlConnection&gt; OpenConnectionAsync(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.OpenConnectionAsync(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionAsync (connectionString As String, options As ConnectionOptions) As Task(Of SqlConnection)" />
      <MemberSignature Language="F#" Value="member this.OpenConnectionAsync : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions -&gt; System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;" Usage="shard.OpenConnectionAsync (connectionString, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions" />
      </Parameters>
      <Docs>
        <param name="connectionString">
            SQL Server 資格情報または統合セキュリティの設定などの資格情報で接続文字列です。 サーバーと、データベース、シャードの名前のホスト名は、キーの参照操作から取得されます。
            </param>
        <param name="options">検証操作で実行するためのオプションには、接続が開かれます。</param>
        <summary>
            非同期的に、通常<see cref="T:System.Data.SqlClient.SqlConnection" />指定のシャードにします。
            </summary>
        <returns>開かれた SqlConnection をカプセル化タスク</returns>
        <remarks>
            なお、<see cref="T:System.Data.SqlClient.SqlConnection" />この呼び出しによって返されるオブジェクトが一時的なエラーから保護されていません。 呼び出し元は、transient fault handling Microsoft Patterns and Practices チームからの Enterprise Library の機能を使用して、アプリケーション コードで、たとえば、一時的なエラーへの接続を保護するベスト プラクティスに従う必要があります。
            使用状況以外のすべてのエラーは返されたタスクによって伝達されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="shard.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを文字列形式に変換します。
            </summary>
        <returns>オブジェクトの文字列表現。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
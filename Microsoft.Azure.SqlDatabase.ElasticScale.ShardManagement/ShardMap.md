<Type Name="ShardMap" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap">
  <TypeSignature Language="C#" Value="public abstract class ShardMap" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ShardMap extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ShardMap" />
  <TypeSignature Language="F#" Value="type ShardMap = class&#xA;    interface ICloneable&lt;ShardMap&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            シャードとキーと、コレクション内のシャード間のマッピングのコレクションを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CloneCore">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap CloneCore ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap CloneCore() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.CloneCore" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function CloneCore () As ShardMap" />
      <MemberSignature Language="F#" Value="abstract member CloneCore : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" Usage="shardMap.CloneCore " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在のシャード マップのインスタンスを複製します。
            </summary>
        <returns>複製されたシャード マップのインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateShard">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard CreateShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardCreationInfo shardCreationArgs);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard CreateShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardCreationInfo shardCreationArgs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.CreateShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardCreationInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateShard (shardCreationArgs As ShardCreationInfo) As Shard" />
      <MemberSignature Language="F#" Value="member this.CreateShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardCreationInfo -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" Usage="shardMap.CreateShard shardCreationArgs" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardCreationArgs" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardCreationInfo" />
      </Parameters>
      <Docs>
        <param name="shardCreationArgs">追加するシャードについて説明します。</param>
        <summary>
            新しいシャードを作成し、シャードのマップを登録します。
            </summary>
        <returns>新しいシャードは、このシャード マップに登録します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateShard">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard CreateShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard CreateShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.CreateShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateShard (location As ShardLocation) As Shard" />
      <MemberSignature Language="F#" Value="member this.CreateShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" Usage="shardMap.CreateShard location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
      </Parameters>
      <Docs>
        <param name="location">追加するシャードの場所です。</param>
        <summary>
            アトミックに指定された場所を使用して ShardMap にシャードを追加します。
            </summary>
        <returns>このシャード マップに接続されているシャードです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteShard">
      <MemberSignature Language="C#" Value="public void DeleteShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.DeleteShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard)" />
      <MemberSignature Language="F#" Value="member this.DeleteShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard -&gt; unit" Usage="shardMap.DeleteShard shard" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shard" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
      </Parameters>
      <Docs>
        <param name="shard">シャードを削除します。</param>
        <summary>
            ShardMap から、シャードを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShard">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard GetShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard GetShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.GetShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShard (location As ShardLocation) As Shard" />
      <MemberSignature Language="F#" Value="member this.GetShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" Usage="shardMap.GetShard location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
      </Parameters>
      <Docs>
        <param name="location">シャードの場所です。</param>
        <summary>
            指定された場所のシャードを取得します。
            </summary>
        <returns>指定された場所が含まれるシャードです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShards">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt; GetShards ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt; GetShards() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.GetShards" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShards () As IEnumerable(Of Shard)" />
      <MemberSignature Language="F#" Value="member this.GetShards : unit -&gt; seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt;" Usage="shardMap.GetShards " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1024:UsePropertiesWhereAppropriate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            シャードのマップからすべてのシャードを取得します。
            </summary>
        <returns>すべてのシャードがシャード マップに属しています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType KeyType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType KeyType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.KeyType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyType As ShardKeyType" />
      <MemberSignature Language="F#" Value="member this.KeyType : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.KeyType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardKeyType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>シャードのマップのキーの型。</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MapType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType MapType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType MapType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.MapType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MapType As ShardMapType" />
      <MemberSignature Language="F#" Value="member this.MapType : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.MapType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>シャード マップの種類。</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>シャード マップの名前です。</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionForKey&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public System.Data.SqlClient.SqlConnection OpenConnectionForKey&lt;TKey&gt; (TKey key, string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.SqlClient.SqlConnection OpenConnectionForKey&lt;TKey&gt;(!!TKey key, string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.OpenConnectionForKey``1(``0,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionForKey(Of TKey) (key As TKey, connectionString As String) As SqlConnection" />
      <MemberSignature Language="F#" Value="member this.OpenConnectionForKey : 'Key * string -&gt; System.Data.SqlClient.SqlConnection" Usage="shardMap.OpenConnectionForKey (key, connectionString)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.SqlClient.SqlConnection</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">キーの型。</typeparam>
        <param name="key">キーの値を入力します。</param>
        <param name="connectionString">
            SQL Server 資格情報または統合セキュリティの設定などの資格情報で接続文字列です。 サーバーと、データベース、シャードの名前のホスト名は、キーの参照操作から取得されます。
            </param>
        <summary>
            開き、通常<see cref="T:System.Data.SqlClient.SqlConnection" />、指定したキー値がマップされているシャードと<see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />です。
            </summary>
        <returns>開かれた SqlConnection でです。</returns>
        <remarks>
            なお、<see cref="T:System.Data.SqlClient.SqlConnection" />この呼び出しによって返されるオブジェクトが一時的なエラーから保護されていません。 呼び出し元は、transient fault handling Microsoft Patterns and Practices チームからの Enterprise Library の機能を使用して、アプリケーション コードで、たとえば、一時的なエラーへの接続を保護するベスト プラクティスに従う必要があります。
            この呼び出しは、1 つの既定のマッピングがある場合にのみ機能します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionForKey&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public System.Data.SqlClient.SqlConnection OpenConnectionForKey&lt;TKey&gt; (TKey key, string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.SqlClient.SqlConnection OpenConnectionForKey&lt;TKey&gt;(!!TKey key, string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.OpenConnectionForKey``1(``0,System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionForKey(Of TKey) (key As TKey, connectionString As String, options As ConnectionOptions) As SqlConnection" />
      <MemberSignature Language="F#" Value="member this.OpenConnectionForKey : 'Key * string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions -&gt; System.Data.SqlClient.SqlConnection" Usage="shardMap.OpenConnectionForKey (key, connectionString, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.SqlClient.SqlConnection</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">キーの型。</typeparam>
        <param name="key">キーの値を入力します。</param>
        <param name="connectionString">
            SQL Server 資格情報または統合セキュリティの設定などの資格情報で接続文字列です。 サーバーと、データベース、シャードの名前のホスト名は、キーの参照操作から取得されます。
            </param>
        <param name="options">検証操作で実行するためのオプションには、接続が開かれます。</param>
        <summary>
            開き、通常<see cref="T:System.Data.SqlClient.SqlConnection" />指定のキー値をマップするシャードにします。
            </summary>
        <returns>開かれた SqlConnection でです。</returns>
        <remarks>
            なお、<see cref="T:System.Data.SqlClient.SqlConnection" />この呼び出しによって返されるオブジェクトが一時的なエラーから保護されていません。 呼び出し元は、transient fault handling Microsoft Patterns and Practices チームからの Enterprise Library の機能を使用して、アプリケーション コードで、たとえば、一時的なエラーへの接続を保護するベスト プラクティスに従う必要があります。
            この呼び出しは、1 つの既定のマッピングがある場合にのみ機能します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionForKeyAsync&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt; OpenConnectionForKeyAsync&lt;TKey&gt; (TKey key, string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.SqlClient.SqlConnection&gt; OpenConnectionForKeyAsync&lt;TKey&gt;(!!TKey key, string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.OpenConnectionForKeyAsync``1(``0,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionForKeyAsync(Of TKey) (key As TKey, connectionString As String) As Task(Of SqlConnection)" />
      <MemberSignature Language="F#" Value="member this.OpenConnectionForKeyAsync : 'Key * string -&gt; System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;" Usage="shardMap.OpenConnectionForKeyAsync (key, connectionString)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">キーの型。</typeparam>
        <param name="key">キーの値を入力します。</param>
        <param name="connectionString">
            SQL Server 資格情報または統合セキュリティの設定などの資格情報で接続文字列です。 サーバーと、データベース、シャードの名前のホスト名は、キーの参照操作から取得されます。
            </param>
        <summary>
            非同期的に開き、通常<see cref="T:System.Data.SqlClient.SqlConnection" />、指定したキー値がマップされているシャードと<see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />です。
            </summary>
        <returns>開かれた SqlConnection をカプセル化するタスク。</returns>
        <remarks>
            なお、<see cref="T:System.Data.SqlClient.SqlConnection" />この呼び出しによって返されるオブジェクトが一時的なエラーから保護されていません。 呼び出し元は、transient fault handling Microsoft Patterns and Practices チームからの Enterprise Library の機能を使用して、アプリケーション コードで、たとえば、一時的なエラーへの接続を保護するベスト プラクティスに従う必要があります。
            この呼び出しは、1 つの既定のマッピングがある場合にのみ機能します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionForKeyAsync&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt; OpenConnectionForKeyAsync&lt;TKey&gt; (TKey key, string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.SqlClient.SqlConnection&gt; OpenConnectionForKeyAsync&lt;TKey&gt;(!!TKey key, string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.OpenConnectionForKeyAsync``1(``0,System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionForKeyAsync(Of TKey) (key As TKey, connectionString As String, options As ConnectionOptions) As Task(Of SqlConnection)" />
      <MemberSignature Language="F#" Value="member this.OpenConnectionForKeyAsync : 'Key * string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions -&gt; System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;" Usage="shardMap.OpenConnectionForKeyAsync (key, connectionString, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">キーの型。</typeparam>
        <param name="key">キーの値を入力します。</param>
        <param name="connectionString">
            SQL Server 資格情報または統合セキュリティの設定などの資格情報で接続文字列です。 サーバーと、データベース、シャードの名前のホスト名は、キーの参照操作から取得されます。
            </param>
        <param name="options">検証操作で実行するためのオプションには、接続が開かれます。</param>
        <summary>
            非同期的に開き、通常<see cref="T:System.Data.SqlClient.SqlConnection" />指定のキー値をマップするシャードにします。
            </summary>
        <returns>開かれた SqlConnection をカプセル化するタスク。</returns>
        <remarks>
            なお、<see cref="T:System.Data.SqlClient.SqlConnection" />この呼び出しによって返されるオブジェクトが一時的なエラーから保護されていません。 呼び出し元は、transient fault handling Microsoft Patterns and Practices チームからの Enterprise Library の機能を使用して、アプリケーション コードで、たとえば、一時的なエラーへの接続を保護するベスト プラクティスに従う必要があります。
            この呼び出しは、1 つの既定のマッピングがある場合にのみ機能します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="shardMap.ToString " />
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
    <Member MemberName="TryGetShard">
      <MemberSignature Language="C#" Value="public bool TryGetShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&amp; shard) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap.TryGetShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetShard (location As ShardLocation, ByRef shard As Shard) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation *  -&gt; bool" Usage="shardMap.TryGetShard (location, shard)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="shard" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="location">シャードの場所です。</param>
        <param name="shard">指定された場所が含まれるシャードです。</param>
        <summary>
            指定された場所のシャードを取得しようとしています。
            </summary>
        <returns>
          <c>true</c>指定場所で分割が見つかった場合、 <c>false</c>それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="SchemaInfoCollection" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection">
  <TypeSignature Language="C#" Value="public class SchemaInfoCollection : System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;string,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SchemaInfoCollection extends System.Object implements class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&gt;&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection" />
  <TypeSignature Language="VB.NET" Value="Public Class SchemaInfoCollection&#xA;Implements IEnumerable(Of KeyValuePair(Of String, SchemaInfo))" />
  <TypeSignature Language="F#" Value="type SchemaInfoCollection = class&#xA;    interface seq&lt;KeyValuePair&lt;string, SchemaInfo&gt;&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            クライアントに storing\updating\retrieving スキーマについては、分割スキームに関連付けられているし、情報の個々 のバケットに名前を割り当てる記憶域サービスを提供します。 クラスは、分割スキームとメタデータのユニット間の関連付けを格納しません。 マッピングを維持するために、呼び出し元の役割です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (string shardMapName, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo schemaInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Add(string shardMapName, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo schemaInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection.Add(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo)" />
      <MemberSignature Language="F#" Value="member this.Add : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo -&gt; unit" Usage="schemaInfoCollection.Add (shardMapName, schemaInfo)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
        <Parameter Name="schemaInfo" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />
      </Parameters>
      <Docs>
        <param name="shardMapName">名前、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />を<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />が関連付けられる</param>
        <param name="schemaInfo">シャーディングのスキーマ情報。</param>
        <summary>
            追加、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />と関連付けられている、指定された<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />名。 関連付けられているデータには、シャーディングされたテーブルと参照テーブルに関する情報が含まれています。 追加しようとする場合、 <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> 、既存の名前と、名前が競合例外がスローされます
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo Get (string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo Get(string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection.Get(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Get (shardMapName As String) As SchemaInfo" />
      <MemberSignature Language="F#" Value="member this.Get : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" Usage="schemaInfoCollection.Get shardMapName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardMapName">取得する <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> の名前。</param>
        <summary>
            フェッチ、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />と共に、指定された格納<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />名。
            </summary>
        <returns>SchemaInfo オブジェクトです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&gt;&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&gt;&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of KeyValuePair(Of String, SchemaInfo))" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&gt;&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&gt;&gt;" Usage="schemaInfoCollection.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection" /> を反復処理する列挙子を返します。
            </summary>
        <returns>名前のキー/値ペアの列挙子と<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public void Remove (string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Remove(string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection.Remove(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Remove (shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.Remove : string -&gt; unit" Usage="schemaInfoCollection.Remove shardMapName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardMapName">名前、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />が<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />は削除されます</param>
        <summary>
            削除、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />と、指定された<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />名。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Replace">
      <MemberSignature Language="C#" Value="public void Replace (string shardMapName, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo schemaInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Replace(string shardMapName, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo schemaInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection.Replace(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo)" />
      <MemberSignature Language="F#" Value="member this.Replace : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo -&gt; unit" Usage="schemaInfoCollection.Replace (shardMapName, schemaInfo)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
        <Parameter Name="schemaInfo" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />
      </Parameters>
      <Docs>
        <param name="shardMapName">名前、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />が<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />は置き換えられます。</param>
        <param name="schemaInfo">シャーディングのスキーマ情報。</param>
        <summary>
            置換、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />と、指定された<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />名。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            これを反復処理する列挙子を返します<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection" />です。
            </summary>
        <returns>名前のキー/値ペアの列挙子と<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGet">
      <MemberSignature Language="C#" Value="public bool TryGet (string shardMapName, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo schemaInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGet(string shardMapName, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&amp; schemaInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection.TryGet(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGet (shardMapName As String, ByRef schemaInfo As SchemaInfo) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGet : string *  -&gt; bool" Usage="schemaInfoCollection.TryGet (shardMapName, schemaInfo)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
        <Parameter Name="schemaInfo" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="shardMapName">名前、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />が<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />がフェッチされます</param>
        <param name="schemaInfo"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />フェッチや取得が失敗した場合は、null でした</param>
        <summary>
            フェッチしようとする、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />と、指定された<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />データが存在しない場合は、任意の例外を生成せずに名前。
            </summary>
        <returns>指定した名前、false スキーマ情報がそれが存在する場合は true。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
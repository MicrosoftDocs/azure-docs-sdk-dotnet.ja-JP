<Type Name="RecoveryManager" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager">
  <TypeSignature Language="C#" Value="public sealed class RecoveryManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RecoveryManager extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RecoveryManager" />
  <TypeSignature Language="F#" Value="type RecoveryManager = class" />
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
            さまざまな回復を管理するシャードのマップ manager に関連するタスク。 シャード マップの情報およびグローバル シャードのマップ manager データベース、シャードにローカルに格納されている間のデータ破損の問題を解決するのに役立ちます。 また、特定の '不測' データベースのバックアップまたはデータベース コピー数のシャード マップの再構築が必要な回復シナリオ。
            </summary>
    <remarks>
            いる一部の回復方法が不可能なデータ失われること正しく使用されていないときに注意してください。 バックアップまたは回復操作に参加するすべてのデータベースのコピーをお勧めします。 
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AttachShard">
      <MemberSignature Language="C#" Value="public void AttachShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AttachShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.AttachShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AttachShard (location As ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.AttachShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; unit" Usage="recoveryManager.AttachShard location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
      </Parameters>
      <Docs>
        <param name="location">アタッチされている、シャードの場所です。</param>
        <summary>
            シャードをシャードのマップ マネージャーにアタッチします。 アタッチするシャード上でより新しいバージョンが見つかった場合、同じシャード マップのマッピングの以前のバージョンが自動的に更新されます。
            シャードをアタッチした後<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />手動を保証する不整合競合解決のチェックに呼び出す必要があります。
            </summary>
        <remarks>
            このメソッドが不可能なデータ損失を招くことに注意してください。 バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AttachShard">
      <MemberSignature Language="C#" Value="public void AttachShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AttachShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.AttachShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AttachShard (location As ShardLocation, shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.AttachShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * string -&gt; unit" Usage="recoveryManager.AttachShard (location, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Maintainability", "CA1502:AvoidExcessiveComplexity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">アタッチされている、シャードの場所です。</param>
        <param name="shardMapName">シャード マップ名でフィルター処理する省略可能です。</param>
        <summary>
            シャードをシャードのマップ マネージャーにアタッチします。 アタッチするシャード上でより新しいバージョンが見つかった場合、同じシャード マップのマッピングの以前のバージョンが自動的に更新されます。
            シャードの場所は、この操作の一部としてローカル ストアの最新バージョンにアップグレードされます。
            シャードをアタッチした後<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />手動を保証する不整合競合解決のチェックに呼び出す必要があります。
            </summary>
        <remarks>
            このメソッドが不可能なデータ損失を招くことに注意してください。 バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DetachShard">
      <MemberSignature Language="C#" Value="public void DetachShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DetachShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetachShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DetachShard (location As ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.DetachShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; unit" Usage="recoveryManager.DetachShard location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
      </Parameters>
      <Docs>
        <param name="location">デタッチするシャードの場所です。</param>
        <summary>
            シャードのマップ マネージャーから特定のシャードをデタッチします。 マッピングを削除するシャードを指すは、このメソッドによって自動的に削除されます。
            </summary>
        <remarks>
            このメソッドが不可能なデータ損失を招くことに注意してください。 バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DetachShard">
      <MemberSignature Language="C#" Value="public void DetachShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DetachShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetachShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DetachShard (location As ShardLocation, shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.DetachShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * string -&gt; unit" Usage="recoveryManager.DetachShard (location, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">デタッチするシャードの場所です。</param>
        <param name="shardMapName">シャード マップ名でフィルター処理する省略可能です。</param>
        <summary>
            シャードのマップ マネージャーから特定のシャードをデタッチします。 マッピングを削除するシャードを指すは、このメソッドによって自動的に削除されます。
            </summary>
        <remarks>
            このメソッドが不可能なデータ損失を招くことに注意してください。 バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DetectMappingDifferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt; DetectMappingDifferences (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt; DetectMappingDifferences(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function DetectMappingDifferences (location As ShardLocation) As IEnumerable(Of RecoveryToken)" />
      <MemberSignature Language="F#" Value="member this.DetectMappingDifferences : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;" Usage="recoveryManager.DetectMappingDifferences location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
      </Parameters>
      <Docs>
        <param name="location">不整合が検出する対象のシャードの場所です。</param>
        <summary>
            シャードを指定した場所にグローバル シャードのマップ manager データベースとシャードのローカルのデータベースのマッピングでの違いを列挙します。
            </summary>
        <returns>さらに解決タスクに使用されるトークンのコレクション (を参照してください<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />)。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetectMappingDifferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt; DetectMappingDifferences (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt; DetectMappingDifferences(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DetectMappingDifferences (location As ShardLocation, shardMapName As String) As IEnumerable(Of RecoveryToken)" />
      <MemberSignature Language="F#" Value="member this.DetectMappingDifferences : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * string -&gt; seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;" Usage="recoveryManager.DetectMappingDifferences (location, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Maintainability", "CA1506:AvoidExcessiveClassCoupling")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Maintainability", "CA1502:AvoidExcessiveComplexity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">不整合が検出する対象のシャードの場所です。</param>
        <param name="shardMapName">特定のシャード マップを指定する省略可能なパラメーターです。</param>
        <summary>
            シャードを指定した場所にグローバル シャードのマップ manager データベースとシャードのローカルのデータベースのマッピングでの違いを列挙します。
            </summary>
        <returns>さらに解決タスクに使用されるトークンのコレクション (を参照してください<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />)。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappingDifferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation&gt; GetMappingDifferences (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IDictionary`2&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation&gt; GetMappingDifferences(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMappingDifferences (token As RecoveryToken) As IDictionary(Of ShardRange, MappingLocation)" />
      <MemberSignature Language="F#" Value="member this.GetMappingDifferences : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; System.Collections.Generic.IDictionary&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation&gt;" Usage="recoveryManager.GetMappingDifferences token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="token">返された回復トークン<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</param>
        <summary>
            範囲-場所キー/値ペアのディクショナリを返します。 返される場所は、特定の範囲 (またはポイント) がのみローカル シャードのマップだけでは、グローバル シャード マップ、またはその両方に存在するかどうかを示す、列挙子です。 範囲のいずれかのシャードのマップに含まれていないは、これらの範囲が表示されないようにの相違点を含めることはできません。
            </summary>
        <returns>範囲のセットとそれに対応する<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation" />です。</returns>
        <remarks>
            この方法では、前の呼び出しに<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />回復トークン パラメーターを提供します。
            などの不整合を解決するのには後続の呼び出しでこのメソッドの結果が通常使用される<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />または<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange})" />です。 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardInfo">
      <MemberSignature Language="C#" Value="public void GetShardInfo (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType mapType, out string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetShardInfo(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, [out] valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType&amp; mapType, [out] string&amp; shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardInfo(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType@,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetShardInfo (token As RecoveryToken, ByRef mapType As ShardMapType, ByRef shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.GetShardInfo : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken *  *  -&gt; unit" Usage="recoveryManager.GetShardInfo (token, mapType, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="1#")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="2#")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
        <Parameter Name="mapType" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType&amp;" RefType="out" />
        <Parameter Name="shardMapName" Type="System.String&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="token">返された回復トークン<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</param>
        <param name="mapType">Shardmap 型 (範囲またはリスト) を出力します。</param>
        <param name="shardMapName">シャード マップの名前を出力します。</param>
        <summary>
            シャード マップの種類から返されたトークンに基づく名前を取得<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardInfo">
      <MemberSignature Language="C#" Value="public void GetShardInfo (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType mapType, out string shardMapName, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetShardInfo(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, [out] valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType&amp; mapType, [out] string&amp; shardMapName, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&amp; shardLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardInfo(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType@,System.String@,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation@)" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetShardInfo (token As RecoveryToken, ByRef mapType As ShardMapType, ByRef shardMapName As String, ByRef shardLocation As ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.GetShardInfo : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken *  *  *  -&gt; unit" Usage="recoveryManager.GetShardInfo (token, mapType, shardMapName, shardLocation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="3#")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="1#")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="2#")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
        <Parameter Name="mapType" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType&amp;" RefType="out" />
        <Parameter Name="shardMapName" Type="System.String&amp;" RefType="out" />
        <Parameter Name="shardLocation" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="token">返された回復トークン<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</param>
        <param name="mapType">出力のシャード マップの種類 (範囲またはリスト)。</param>
        <param name="shardMapName">シャード マップ名を出力します。</param>
        <param name="shardLocation">出力のシャードの場所</param>
        <summary>
            シャード マップの種類、名前、およびシャードの場所を取得から返されたトークンに基づく<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardLocation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation GetShardLocation (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation GetShardLocation(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardLocation(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShardLocation (token As RecoveryToken) As ShardLocation" />
      <MemberSignature Language="F#" Value="member this.GetShardLocation : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" Usage="recoveryManager.GetShardLocation token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="token">返されたトークンの回復<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /></param>
        <summary>
            によって処理されるローカルのシャードのマップのシャードの場所を返します<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。
            </summary>
        <returns>相違点の検出のマッピングのセットに対応するシャードの場所<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardMapName">
      <MemberSignature Language="C#" Value="public string GetShardMapName (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetShardMapName(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardMapName(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShardMapName (token As RecoveryToken) As String" />
      <MemberSignature Language="F#" Value="member this.GetShardMapName : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; string" Usage="recoveryManager.GetShardMapName token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="token">返された回復トークン<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</param>
        <summary>
            によって処理されたシャードのマップのシャード マップ名を返します<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。
            </summary>
        <returns>指定した回復トークンのシャードのマップの名前。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardMapType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType GetShardMapType (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType GetShardMapType(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardMapType(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShardMapType (token As RecoveryToken) As ShardMapType" />
      <MemberSignature Language="F#" Value="member this.GetShardMapType : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType" Usage="recoveryManager.GetShardMapType token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="token">返された回復トークン<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</param>
        <summary>
            によって処理されたシャードのマップのシャード マップの種類を返します<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。
            </summary>
        <returns>回復のトークンに対応するシャード マップ (リスト、範囲など) の型。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShard">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt; ranges);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt; ranges) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShard (token As RecoveryToken, ranges As IEnumerable(Of ShardRange))" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken * seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt; -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShard (token, ranges)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="1")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
        <Parameter Name="ranges" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt;" />
      </Parameters>
      <Docs>
        <param name="token">以前の呼び出しから回復トークン<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</param>
        <param name="ranges">ローカル シャードのマップを再構築するときに、ローカルのシャードに保持する範囲のセット。</param>
        <summary>
             によって検出された一貫性のないシャードの範囲の一覧からローカル範囲シャード マップを再構築<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />にアクセスして、<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />です。
             結果として得られるローカル範囲シャード マップが常にまだされませんと一致するシャードのマップ manager データベース内のグローバル シャード マップします。 後続の呼び出しに<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />は正常な状態に戻す、システムを表示するために必要です。
             </summary>
        <remarks>
             このメソッドが不可能なデータ損失を招くことに注意してください。 バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。
             
            不整合をシャードの範囲内だけは、このメソッドを使用して再構築することができます。 なしの不一致は、ローカルのシャードとグローバル シャードのマップをすべての範囲内では、ローカルのシャードに完全な状態で保持され、この呼び出しの影響は受けません。
             シャードのマップ マネージャーで正規のインターフェイスを使用して後で、競合しないマッピングを後続の変更ができます。 回復マネージャーを使用して、競合しないマッピングを変更する必要はありません。
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShardMapManagerFromShards">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShardMapManagerFromShards (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShardMapManagerFromShards(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShardMapManagerFromShards(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShardMapManagerFromShards (shardLocations As IEnumerable(Of ShardLocation))" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShardMapManagerFromShards : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShardMapManagerFromShards shardLocations" />
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
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
      </Parameters>
      <Docs>
        <param name="shardLocations">シャードの場所のコレクション。</param>
        <summary>
            指定した場所のシャードのコレクション、個々 のシャードに格納されているマッピング情報に基づいてシャードのマップ マネージャーを再構築します。 指定されたシャードは、グローバルのシャードのマップに既に登録する必要があります。 このメソッドには、マッピングだけ再構築します。 グローバルのシャードのマップ内のメンバーシップのシャードを再構築にはできません。
            個々 のシャード マップの情報は、不整合が発生した場合、動作は定義されません。
            クロス シャード ロックは行われませんため、シャードは、このメソッドの実行中に不整合になると、グローバル シャードのマップの最終的な状態は破損している可能性があります。
            </summary>
        <remarks>
            このメソッドが不可能なデータ損失を招くことに注意してください。 バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShardMapManagerFromShards">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShardMapManagerFromShards (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShardMapManagerFromShards(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShardMapManagerFromShards(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShardMapManagerFromShards (shardLocations As IEnumerable(Of ShardLocation), shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShardMapManagerFromShards : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; * string -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShardMapManagerFromShards (shardLocations, shardMapName)" />
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
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardLocations">シャードの場所のコレクション。</param>
        <param name="shardMapName">シャード マップのオプションの名前。 省略した場合は、各シャードにあるすべてのシャード マップからの回復を試みます。</param>
        <summary>
            指定した場所のシャードのコレクション、個々 のシャードに格納されているマッピング情報に基づいてシャードのマップ マネージャーを再構築します。 指定されたシャードは、グローバルのシャードのマップに既に登録する必要があります。 このメソッドには、マッピングだけ再構築します。 グローバルのシャードのマップ内のメンバーシップのシャードを再構築にはできません。
            個々 のシャード マップの情報は、不整合が発生した場合、動作は定義されません。
            クロス シャード ロックは行われませんため、シャードは、このメソッドの実行中に不整合になると、グローバル シャードのマップの最終的な状態は破損している可能性があります。
            </summary>
        <remarks>
            このメソッドが不可能なデータ損失を招くことに注意してください。 バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShardsFromShardMapManager">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShardsFromShardMapManager (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShardsFromShardMapManager(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShardsFromShardMapManager(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShardsFromShardMapManager (shardLocations As IEnumerable(Of ShardLocation))" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShardsFromShardMapManager : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShardsFromShardMapManager shardLocations" />
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
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
      </Parameters>
      <Docs>
        <param name="shardLocations">シャードの場所のコレクション。</param>
        <summary>
            シャードの場所のコレクションを指定するには、ローカルのシャードのマップを再構築は、グローバルのシャードのマップに格納されているマッピング情報に基づいています。 指定されたシャードは、グローバルのシャードのマップに既に登録する必要があります。 このメソッドには、マッピングだけ再構築します。 グローバルのシャードのマップ内のメンバーシップのシャードを再構築にはできません。
            </summary>
        <remarks>
            このメソッドが不可能なデータ損失を招くことに注意してください。 バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShardsFromShardMapManager">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShardsFromShardMapManager (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShardsFromShardMapManager(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShardsFromShardMapManager(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShardsFromShardMapManager (shardLocations As IEnumerable(Of ShardLocation), shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShardsFromShardMapManager : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; * string -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShardsFromShardMapManager (shardLocations, shardMapName)" />
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
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardLocations">シャードの場所のコレクション。</param>
        <param name="shardMapName">シャード マップ名でフィルター処理する省略可能なパラメーターです。 省略した場合、すべてのシャード マップが再構築されます。</param>
        <summary>
            シャードの場所のコレクションを指定するには、ローカルのシャードのマップを再構築は、グローバルのシャードのマップに格納されているマッピング情報に基づいています。 指定されたシャードは、グローバルのシャードのマップに既に登録する必要があります。 このメソッドには、マッピングだけ再構築します。 グローバルのシャードのマップ内のメンバーシップのシャードを再構築にはできません。
            </summary>
        <remarks>
            このメソッドが不可能なデータ損失を招くことに注意してください。 バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveMappingDifferences">
      <MemberSignature Language="C#" Value="public void ResolveMappingDifferences (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution resolution);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResolveMappingDifferences(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution resolution) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResolveMappingDifferences (token As RecoveryToken, resolution As MappingDifferenceResolution)" />
      <MemberSignature Language="F#" Value="member this.ResolveMappingDifferences : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution -&gt; unit" Usage="recoveryManager.ResolveMappingDifferences (token, resolution)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
        <Parameter Name="resolution" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution" />
      </Parameters>
      <Docs>
        <param name="token">返された回復トークン<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />です。</param>
        <param name="resolution">解決に使用する解決方法です。</param>
        <summary>
            情報源として、シャード マップ (ローカルまたはグローバルのいずれか) のいずれかを選択し、両方の同期のシャード マップ上のマッピングを表示します。
            </summary>
        <remarks>
            このメソッドが不可能なデータ損失を招くことに注意してください。 バックアップまたはデータベースのコピーを取得した、慎重に進みます. のみを確認してください。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
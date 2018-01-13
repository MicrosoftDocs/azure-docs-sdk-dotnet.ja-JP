<Type Name="ListShardMap&lt;TKey&gt;" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt;">
  <TypeSignature Language="C#" Value="public sealed class ListShardMap&lt;TKey&gt; : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListShardMap`1&lt;TKey&gt; extends Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListShardMap(Of TKey)&#xA;Inherits ShardMap" />
  <TypeSignature Language="F#" Value="type ListShardMap&lt;'Key&gt; = class&#xA;    inherit ShardMap&#xA;    interface ICloneable&lt;ShardMap&gt;&#xA;    interface ICloneable&lt;ListShardMap&lt;'Key&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TKey" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TKey">キーの型。</typeparam>
    <summary>
            指定したキーのポイントのあるポイントのシャード マップを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt; Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1&lt;!TKey&gt; Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As ListShardMap(Of TKey)" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;'Key&gt;&#xA;override this.Clone : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;'Key&gt;" Usage="listShardMap.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ICloneable`1.Clone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            指定されたリストのシャードのマップを複製します。
            </summary>
        <returns>一覧のシャードのマップの複製されたインスタンスです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneCore">
      <MemberSignature Language="C#" Value="protected override Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap CloneCore ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap CloneCore() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.CloneCore" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CloneCore () As ShardMap" />
      <MemberSignature Language="F#" Value="override this.CloneCore : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" Usage="listShardMap.CloneCore " />
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
    <Member MemberName="CreatePointMapping">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; CreatePointMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo&lt;TKey&gt; creationInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; CreatePointMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo`1&lt;!TKey&gt; creationInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.CreatePointMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreatePointMapping (creationInfo As PointMappingCreationInfo(Of TKey)) As PointMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.CreatePointMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo&lt;'Key&gt; -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;" Usage="listShardMap.CreatePointMapping creationInfo" />
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
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creationInfo" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="creationInfo">追加するへのマッピングに関する情報です。</param>
        <summary>
            作成し、ShardMap するポイントのマッピングを追加します。
            </summary>
        <returns>新しく作成されたマッピングです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePointMapping">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; CreatePointMapping (TKey point, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; CreatePointMapping(!TKey point, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.CreatePointMapping(`0,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard)" />
      <MemberSignature Language="F#" Value="member this.CreatePointMapping : 'Key * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;" Usage="listShardMap.CreatePointMapping (point, shard)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="point" Type="TKey" />
        <Parameter Name="shard" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
      </Parameters>
      <Docs>
        <param name="point">マッピングを作成する対象のポイント。</param>
        <param name="shard">ポイントのマッピングに関連付けられているシャードです。</param>
        <summary>
            作成し、ShardMap するポイントのマッピングを追加します。
            </summary>
        <returns>新しく作成されたマッピングです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMapping">
      <MemberSignature Language="C#" Value="public void DeleteMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; mapping);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; mapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.DeleteMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteMapping (mapping As PointMapping(Of TKey))" />
      <MemberSignature Language="F#" Value="member this.DeleteMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt; -&gt; unit" Usage="listShardMap.DeleteMapping mapping" />
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
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="mapping">マッピングが削除されます。</param>
        <summary>
            ポイントのマッピングを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappingForKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; GetMappingForKey (TKey key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; GetMappingForKey(!TKey key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.GetMappingForKey(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMappingForKey (key As TKey) As PointMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.GetMappingForKey : 'Key -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;" Usage="listShardMap.GetMappingForKey key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="key">キーの値を入力します。</param>
        <summary>
            キーの値を検索し、対応するマッピングを返します。
            </summary>
        <returns>マッピングには、キーの値が含まれます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappingLockOwner">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken GetMappingLockOwner (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; mapping);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken GetMappingLockOwner(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; mapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.GetMappingLockOwner(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMappingLockOwner (mapping As PointMapping(Of TKey)) As MappingLockToken" />
      <MemberSignature Language="F#" Value="member this.GetMappingLockOwner : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt; -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" Usage="listShardMap.GetMappingLockOwner mapping" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="mapping">入力範囲のマッピング。</param>
        <summary>
            指定されたマッピングのロック所有者の id を取得します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> のインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&gt; GetMappings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt;&gt; GetMappings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.GetMappings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMappings () As IReadOnlyList(Of PointMapping(Of TKey))" />
      <MemberSignature Language="F#" Value="member this.GetMappings : unit -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;&gt;" Usage="listShardMap.GetMappings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures", Justification="Necessary to allow different types of keys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            シャードのマップのすべてのポイントのマッピングを取得します。
            </summary>
        <returns>シャード マップにポイントへのマッピングをすべての読み取り専用コレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&gt; GetMappings (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt; range);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt;&gt; GetMappings(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1&lt;!TKey&gt; range) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.GetMappings(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMappings (range As Range(Of TKey)) As IReadOnlyList(Of PointMapping(Of TKey))" />
      <MemberSignature Language="F#" Value="member this.GetMappings : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt; -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;&gt;" Usage="listShardMap.GetMappings range" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures", Justification="Necessary to allow different types of keys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="range" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="range">ポイントの値、範囲と重複するマッピングが返されます。</param>
        <summary>
            特定の範囲内に存在するすべてのマッピングを取得します。
            </summary>
        <returns>指定された範囲の制約を満たしているマッピングの読み取り専用のコレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&gt; GetMappings (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt;&gt; GetMappings(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.GetMappings(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard)" />
      <MemberSignature Language="F#" Value="member this.GetMappings : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;&gt;" Usage="listShardMap.GetMappings shard" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures", Justification="Necessary to allow different types of keys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shard" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
      </Parameters>
      <Docs>
        <param name="shard">シャードのマッピングが返されます。</param>
        <summary>
            特定のシャードに存在するすべてのマッピングを取得します。
            </summary>
        <returns>特定のシャードの制約を満たしているマッピングの読み取り専用コレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&gt; GetMappings (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt; range, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt;&gt; GetMappings(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1&lt;!TKey&gt; range, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.GetMappings(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard)" />
      <MemberSignature Language="F#" Value="member this.GetMappings : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;&gt;" Usage="listShardMap.GetMappings (range, shard)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="1")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures", Justification="Necessary to allow different types of keys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="range" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt;" />
        <Parameter Name="shard" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
      </Parameters>
      <Docs>
        <param name="range">ポイントの値、範囲と重複するマッピングが返されます。</param>
        <param name="shard">シャードのマッピングが返されます。</param>
        <summary>
            範囲およびシャード内に存在するすべてのマッピングを取得します。
            </summary>
        <returns>指定された範囲とシャードの制約を満たすためのマッピングの読み取り専用コレクションです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockMapping">
      <MemberSignature Language="C#" Value="public void LockMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; mapping, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void LockMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; mapping, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.LockMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="F#" Value="member this.LockMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; unit" Usage="listShardMap.LockMapping (mapping, mappingLockToken)" />
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
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;" />
        <Parameter Name="mappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="mapping">入力範囲のマッピング。</param>
        <param name="mappingLockToken"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> のインスタンス。</param>
        <summary>
            指定された所有者のみロックの所有者によってロックされているマッピングの状態を変更できますのマッピングをロックします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MarkMappingOffline">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; MarkMappingOffline (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; mapping);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; MarkMappingOffline(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; mapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.MarkMappingOffline(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function MarkMappingOffline (mapping As PointMapping(Of TKey)) As PointMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.MarkMappingOffline : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt; -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;" Usage="listShardMap.MarkMappingOffline mapping" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="mapping">入力のポイントのマッピング。</param>
        <summary>
            指定されたマッピングはオフラインをマークします。
            </summary>
        <returns>オフラインのマッピングです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MarkMappingOnline">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; MarkMappingOnline (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; mapping);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; MarkMappingOnline(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; mapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.MarkMappingOnline(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function MarkMappingOnline (mapping As PointMapping(Of TKey)) As PointMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.MarkMappingOnline : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt; -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;" Usage="listShardMap.MarkMappingOnline mapping" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="mapping">入力のポイントのマッピング。</param>
        <summary>
            指定されたマッピングはオンラインをマークします。
            </summary>
        <returns>オンラインのマッピングです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionForKey">
      <MemberSignature Language="C#" Value="public System.Data.SqlClient.SqlConnection OpenConnectionForKey (TKey key, string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.SqlClient.SqlConnection OpenConnectionForKey(!TKey key, string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.OpenConnectionForKey(`0,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionForKey (key As TKey, connectionString As String) As SqlConnection" />
      <MemberSignature Language="F#" Value="override this.OpenConnectionForKey : 'Key * string -&gt; System.Data.SqlClient.SqlConnection" Usage="listShardMap.OpenConnectionForKey (key, connectionString)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1061:DoNotHideBaseClassMethods")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Data.SqlClient.SqlConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
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
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionForKey">
      <MemberSignature Language="C#" Value="public System.Data.SqlClient.SqlConnection OpenConnectionForKey (TKey key, string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.SqlClient.SqlConnection OpenConnectionForKey(!TKey key, string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.OpenConnectionForKey(`0,System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionForKey (key As TKey, connectionString As String, options As ConnectionOptions) As SqlConnection" />
      <MemberSignature Language="F#" Value="override this.OpenConnectionForKey : 'Key * string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions -&gt; System.Data.SqlClient.SqlConnection" Usage="listShardMap.OpenConnectionForKey (key, connectionString, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1061:DoNotHideBaseClassMethods")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Data.SqlClient.SqlConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions" />
      </Parameters>
      <Docs>
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
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionForKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt; OpenConnectionForKeyAsync (TKey key, string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.SqlClient.SqlConnection&gt; OpenConnectionForKeyAsync(!TKey key, string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.OpenConnectionForKeyAsync(`0,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionForKeyAsync (key As TKey, connectionString As String) As Task(Of SqlConnection)" />
      <MemberSignature Language="F#" Value="override this.OpenConnectionForKeyAsync : 'Key * string -&gt; System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;" Usage="listShardMap.OpenConnectionForKeyAsync (key, connectionString)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1061:DoNotHideBaseClassMethods")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">キーの値を入力します。</param>
        <param name="connectionString">
            SQL Server 資格情報または統合セキュリティの設定などの資格情報で接続文字列です。 サーバーと、データベース、シャードの名前のホスト名は、キーの参照操作から取得されます。
            </param>
        <summary>
            非同期的に開き、通常<see cref="T:System.Data.SqlClient.SqlConnection" />、指定したキー値がマップされているシャードと<see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />です。
            </summary>
        <returns>結果として開く SqlConnection をカプセル化タスク</returns>
        <remarks>
            なお、<see cref="T:System.Data.SqlClient.SqlConnection" />この呼び出しによって返されるオブジェクトが一時的なエラーから保護されていません。 呼び出し元は、transient fault handling Microsoft Patterns and Practices チームからの Enterprise Library の機能を使用して、アプリケーション コードで、たとえば、一時的なエラーへの接続を保護するベスト プラクティスに従う必要があります。
            すべての使用法ではないエラーでは、例外が返されたタスクによって報告された関連します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionForKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt; OpenConnectionForKeyAsync (TKey key, string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.SqlClient.SqlConnection&gt; OpenConnectionForKeyAsync(!TKey key, string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.OpenConnectionForKeyAsync(`0,System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionForKeyAsync (key As TKey, connectionString As String, options As ConnectionOptions) As Task(Of SqlConnection)" />
      <MemberSignature Language="F#" Value="override this.OpenConnectionForKeyAsync : 'Key * string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions -&gt; System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;" Usage="listShardMap.OpenConnectionForKeyAsync (key, connectionString, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1061:DoNotHideBaseClassMethods")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions" />
      </Parameters>
      <Docs>
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
            すべての使用法ではないエラーでは、例外が返されたタスクによって報告された関連します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetMappingForKey">
      <MemberSignature Language="C#" Value="public bool TryGetMappingForKey (TKey key, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; pointMapping);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetMappingForKey(!TKey key, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt;&amp; pointMapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.TryGetMappingForKey(`0,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0}@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetMappingForKey (key As TKey, ByRef pointMapping As PointMapping(Of TKey)) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetMappingForKey : 'Key *  -&gt; bool" Usage="listShardMap.TryGetMappingForKey (key, pointMapping)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="pointMapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="key">キーの値を入力します。</param>
        <param name="pointMapping">マッピングには、キーの値が含まれます。</param>
        <summary>
            キーを検索しよう値し、配置に対応するマッピング<paramref name="pointMapping" />です。
            </summary>
        <returns>
          <c>true</c>マッピングが見つかった場合、 <c>false</c>それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnlockMapping">
      <MemberSignature Language="C#" Value="public void UnlockMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UnlockMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.UnlockMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="F#" Value="member this.UnlockMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; unit" Usage="listShardMap.UnlockMapping mappingLockToken" />
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
        <Parameter Name="mappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="mappingLockToken"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> のインスタンス。</param>
        <summary>
            ロックを解除してに属しているこのマップ内のすべてのマッピングの指定<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnlockMapping">
      <MemberSignature Language="C#" Value="public void UnlockMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; mapping, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UnlockMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; mapping, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.UnlockMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="F#" Value="member this.UnlockMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; unit" Usage="listShardMap.UnlockMapping (mapping, mappingLockToken)" />
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
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;" />
        <Parameter Name="mappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="mapping">入力範囲のマッピング。</param>
        <param name="mappingLockToken"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> のインスタンス。</param>
        <summary>
            指定されたマッピングのロックを解除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMapping">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; UpdateMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; currentMapping, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate update);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; UpdateMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; currentMapping, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate update) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.UpdateMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateMapping (currentMapping As PointMapping(Of TKey), update As PointMappingUpdate) As PointMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.UpdateMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;" Usage="listShardMap.UpdateMapping (currentMapping, update)" />
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
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentMapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;" />
        <Parameter Name="update" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate" />
      </Parameters>
      <Docs>
        <param name="currentMapping">マッピングが更新中です。</param>
        <param name="update">マッピングのプロパティを更新します。</param>
        <summary>
            更新プログラム、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1" />で提供される更新プログラムを<paramref name="update" />パラメーター。
            </summary>
        <returns>更新された情報とマッピングの新しいインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMapping">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; UpdateMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; currentMapping, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate update, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; UpdateMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; currentMapping, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate update, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.UpdateMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;" Usage="listShardMap.UpdateMapping (currentMapping, update, mappingLockToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="2")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentMapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;" />
        <Parameter Name="update" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate" />
        <Parameter Name="mappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="currentMapping">マッピングが更新中です。</param>
        <param name="update">シャードの更新されたプロパティです。</param>
        <param name="mappingLockToken"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> のインスタンス。</param>
        <summary>
            提供される変更点のマッピングを更新、<paramref name="update" />パラメーター。
            </summary>
        <returns>更新された情報とマッピングの新しいインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
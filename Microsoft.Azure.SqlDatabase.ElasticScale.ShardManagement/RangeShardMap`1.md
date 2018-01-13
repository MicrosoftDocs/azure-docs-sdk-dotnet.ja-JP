<Type Name="RangeShardMap&lt;TKey&gt;" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;TKey&gt;">
  <TypeSignature Language="C#" Value="public sealed class RangeShardMap&lt;TKey&gt; : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RangeShardMap`1&lt;TKey&gt; extends Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RangeShardMap(Of TKey)&#xA;Inherits ShardMap" />
  <TypeSignature Language="F#" Value="type RangeShardMap&lt;'Key&gt; = class&#xA;    inherit ShardMap&#xA;    interface ICloneable&lt;ShardMap&gt;&#xA;    interface ICloneable&lt;RangeShardMap&lt;'Key&gt;&gt;" />
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
            範囲のシャード マップを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;TKey&gt; Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1&lt;!TKey&gt; Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As RangeShardMap(Of TKey)" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;'Key&gt;&#xA;override this.Clone : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;'Key&gt;" Usage="rangeShardMap.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ICloneable`1.Clone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            指定された範囲シャードのマップを複製します。
            </summary>
        <returns>範囲シャードのマップの複製インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneCore">
      <MemberSignature Language="C#" Value="protected override Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap CloneCore ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap CloneCore() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.CloneCore" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CloneCore () As ShardMap" />
      <MemberSignature Language="F#" Value="override this.CloneCore : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" Usage="rangeShardMap.CloneCore " />
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
    <Member MemberName="CreateRangeMapping">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; CreateRangeMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingCreationInfo&lt;TKey&gt; creationInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; CreateRangeMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingCreationInfo`1&lt;!TKey&gt; creationInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.CreateRangeMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingCreationInfo{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRangeMapping (creationInfo As RangeMappingCreationInfo(Of TKey)) As RangeMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.CreateRangeMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingCreationInfo&lt;'Key&gt; -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;" Usage="rangeShardMap.CreateRangeMapping creationInfo" />
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
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creationInfo" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingCreationInfo&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="creationInfo">追加するへのマッピングに関する情報です。</param>
        <summary>
            作成し、ShardMap に範囲のマッピングを追加します。
            </summary>
        <returns>新しく作成されたマッピングです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRangeMapping">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; CreateRangeMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt; range, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; CreateRangeMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1&lt;!TKey&gt; range, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.CreateRangeMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard)" />
      <MemberSignature Language="F#" Value="member this.CreateRangeMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;" Usage="rangeShardMap.CreateRangeMapping (range, shard)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="range" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt;" />
        <Parameter Name="shard" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
      </Parameters>
      <Docs>
        <param name="range">マッピングを作成する対象の範囲です。</param>
        <param name="shard">シャードの範囲のマッピングに関連付けられています。</param>
        <summary>
            作成し、ShardMap に範囲のマッピングを追加します。
            </summary>
        <returns>新しく作成されたマッピングです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMapping">
      <MemberSignature Language="C#" Value="public void DeleteMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; mapping);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; mapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.DeleteMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteMapping (mapping As RangeMapping(Of TKey))" />
      <MemberSignature Language="F#" Value="member this.DeleteMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; -&gt; unit" Usage="rangeShardMap.DeleteMapping mapping" />
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
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="mapping">マッピングが削除されます。</param>
        <summary>
            範囲のマッピングを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMapping">
      <MemberSignature Language="C#" Value="public void DeleteMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; mapping, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; mapping, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.DeleteMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; unit" Usage="rangeShardMap.DeleteMapping (mapping, mappingLockToken)" />
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
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="1")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
        <Parameter Name="mappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="mapping">マッピングが削除されます。</param>
        <param name="mappingLockToken"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> のインスタンス。</param>
        <summary>
            範囲のマッピングを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappingForKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; GetMappingForKey (TKey key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; GetMappingForKey(!TKey key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.GetMappingForKey(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMappingForKey (key As TKey) As RangeMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.GetMappingForKey : 'Key -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;" Usage="rangeShardMap.GetMappingForKey key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken GetMappingLockOwner (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; mapping);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken GetMappingLockOwner(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; mapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.GetMappingLockOwner(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMappingLockOwner (mapping As RangeMapping(Of TKey)) As MappingLockToken" />
      <MemberSignature Language="F#" Value="member this.GetMappingLockOwner : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" Usage="rangeShardMap.GetMappingLockOwner mapping" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
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
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;&gt; GetMappings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt;&gt; GetMappings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.GetMappings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMappings () As IReadOnlyList(Of RangeMapping(Of TKey))" />
      <MemberSignature Language="F#" Value="member this.GetMappings : unit -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;&gt;" Usage="rangeShardMap.GetMappings " />
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
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            シャードのマップの範囲のすべてのマッピングを取得します。
            </summary>
        <returns>シャード マップに範囲へのマッピングをすべての読み取り専用コレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;&gt; GetMappings (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt; range);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt;&gt; GetMappings(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1&lt;!TKey&gt; range) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.GetMappings(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMappings (range As Range(Of TKey)) As IReadOnlyList(Of RangeMapping(Of TKey))" />
      <MemberSignature Language="F#" Value="member this.GetMappings : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt; -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;&gt;" Usage="rangeShardMap.GetMappings range" />
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
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="range" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="range">範囲の値、範囲と重複するマッピングが返されます。</param>
        <summary>
            特定の範囲内に存在するすべての範囲のマッピングを取得します。
            </summary>
        <returns>指定された範囲の制約を満たしているマッピングの読み取り専用のコレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;&gt; GetMappings (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt;&gt; GetMappings(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.GetMappings(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard)" />
      <MemberSignature Language="F#" Value="member this.GetMappings : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;&gt;" Usage="rangeShardMap.GetMappings shard" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures", Justification="Necessary to allow different types of keys")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shard" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
      </Parameters>
      <Docs>
        <param name="shard">シャードのマッピングが返されます。</param>
        <summary>
            特定のシャードに存在するすべての範囲のマッピングを取得します。
            </summary>
        <returns>特定のシャードの制約を満たしているマッピングの読み取り専用コレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;&gt; GetMappings (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt; range, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt;&gt; GetMappings(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1&lt;!TKey&gt; range, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.GetMappings(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard)" />
      <MemberSignature Language="F#" Value="member this.GetMappings : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;&gt;" Usage="rangeShardMap.GetMappings (range, shard)" />
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
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="range" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt;" />
        <Parameter Name="shard" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
      </Parameters>
      <Docs>
        <param name="range">範囲の値、範囲と重複するマッピングが返されます。</param>
        <param name="shard">シャードのマッピングが返されます。</param>
        <summary>
            範囲およびシャード内に存在するすべての範囲のマッピングを取得します。
            </summary>
        <returns>指定された範囲とシャードの制約を満たすためのマッピングの読み取り専用コレクションです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockMapping">
      <MemberSignature Language="C#" Value="public void LockMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; mapping, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void LockMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; mapping, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.LockMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="F#" Value="member this.LockMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; unit" Usage="rangeShardMap.LockMapping (mapping, mappingLockToken)" />
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
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; MarkMappingOffline (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; mapping);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; MarkMappingOffline(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; mapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.MarkMappingOffline(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function MarkMappingOffline (mapping As RangeMapping(Of TKey)) As RangeMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.MarkMappingOffline : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;" Usage="rangeShardMap.MarkMappingOffline mapping" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="mapping">入力範囲のマッピング。</param>
        <summary>
            指定されたマッピングはオフラインをマークします。
            </summary>
        <returns>オフラインのマッピングです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MarkMappingOffline">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; MarkMappingOffline (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; mapping, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; MarkMappingOffline(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; mapping, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.MarkMappingOffline(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="F#" Value="member this.MarkMappingOffline : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;" Usage="rangeShardMap.MarkMappingOffline (mapping, mappingLockToken)" />
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
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
        <Parameter Name="mappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="mapping">入力範囲のマッピング。</param>
        <param name="mappingLockToken"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> のインスタンス。</param>
        <summary>
            指定されたマッピングはオフラインをマークします。
            </summary>
        <returns>オフラインのマッピングです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MarkMappingOnline">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; MarkMappingOnline (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; mapping);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; MarkMappingOnline(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; mapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.MarkMappingOnline(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function MarkMappingOnline (mapping As RangeMapping(Of TKey)) As RangeMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.MarkMappingOnline : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;" Usage="rangeShardMap.MarkMappingOnline mapping" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="mapping">入力範囲のマッピング。</param>
        <summary>
            指定されたマッピングはオンラインをマークします。
            </summary>
        <returns>オンラインのマッピングです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MarkMappingOnline">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; MarkMappingOnline (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; mapping, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; MarkMappingOnline(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; mapping, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.MarkMappingOnline(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="F#" Value="member this.MarkMappingOnline : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;" Usage="rangeShardMap.MarkMappingOnline (mapping, mappingLockToken)" />
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
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
        <Parameter Name="mappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="mapping">入力範囲のマッピング。</param>
        <param name="mappingLockToken"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> のインスタンス。</param>
        <summary>
            指定されたマッピングはオンラインをマークします。
            </summary>
        <returns>オンラインのマッピングです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeMappings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; MergeMappings (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; left, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; right);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; MergeMappings(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; left, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.MergeMappings(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function MergeMappings (left As RangeMapping(Of TKey), right As RangeMapping(Of TKey)) As RangeMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.MergeMappings : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;" Usage="rangeShardMap.MergeMappings (left, right)" />
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
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="1")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
        <Parameter Name="right" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="left">左側のマッピング。</param>
        <param name="right">右側のマッピング。</param>
        <summary>
            1 つのマッピングには、2 つの連続したマッピングをマージします。 左と右の両方のマッピングは、同じ場所を指す必要があり、連続している必要があります。
            </summary>
        <returns>マージ操作の結果であるをマッピングします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeMappings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; MergeMappings (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; left, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; right, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken leftMappingLockToken, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken rightMappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; MergeMappings(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; left, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; right, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken leftMappingLockToken, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken rightMappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.MergeMappings(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function MergeMappings (left As RangeMapping(Of TKey), right As RangeMapping(Of TKey), leftMappingLockToken As MappingLockToken, rightMappingLockToken As MappingLockToken) As RangeMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.MergeMappings : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;" Usage="rangeShardMap.MergeMappings (left, right, leftMappingLockToken, rightMappingLockToken)" />
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
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="2")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="3")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="left" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
        <Parameter Name="right" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
        <Parameter Name="leftMappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
        <Parameter Name="rightMappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="left">左側のマッピング。</param>
        <param name="right">右側のマッピング。</param>
        <param name="leftMappingLockToken">インスタンス<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />の左側のマッピング</param>
        <param name="rightMappingLockToken">インスタンス<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />の右側のマッピング</param>
        <summary>
            1 つのマッピングには、2 つの連続したマッピングをマージします。 左と右の両方のマッピングは、同じ場所を指す必要があり、連続している必要があります。
            </summary>
        <returns>マージ操作の結果であるをマッピングします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionForKey">
      <MemberSignature Language="C#" Value="public System.Data.SqlClient.SqlConnection OpenConnectionForKey (TKey key, string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.SqlClient.SqlConnection OpenConnectionForKey(!TKey key, string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.OpenConnectionForKey(`0,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionForKey (key As TKey, connectionString As String) As SqlConnection" />
      <MemberSignature Language="F#" Value="override this.OpenConnectionForKey : 'Key * string -&gt; System.Data.SqlClient.SqlConnection" Usage="rangeShardMap.OpenConnectionForKey (key, connectionString)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.OpenConnectionForKey(`0,System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionForKey (key As TKey, connectionString As String, options As ConnectionOptions) As SqlConnection" />
      <MemberSignature Language="F#" Value="override this.OpenConnectionForKey : 'Key * string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions -&gt; System.Data.SqlClient.SqlConnection" Usage="rangeShardMap.OpenConnectionForKey (key, connectionString, options)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.OpenConnectionForKeyAsync(`0,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionForKeyAsync (key As TKey, connectionString As String) As Task(Of SqlConnection)" />
      <MemberSignature Language="F#" Value="override this.OpenConnectionForKeyAsync : 'Key * string -&gt; System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;" Usage="rangeShardMap.OpenConnectionForKeyAsync (key, connectionString)" />
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
        <returns>開かれた SqlConnection をカプセル化するタスク。</returns>
        <remarks>
            なお、<see cref="T:System.Data.SqlClient.SqlConnection" />この呼び出しによって返されるオブジェクトが一時的なエラーから保護されていません。 呼び出し元は、transient fault handling Microsoft Patterns and Practices チームからの Enterprise Library の機能を使用して、アプリケーション コードで、たとえば、一時的なエラーへの接続を保護するベスト プラクティスに従う必要があります。
            使用状況以外のすべてのエラーは返されたタスクによって伝達されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionForKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt; OpenConnectionForKeyAsync (TKey key, string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.SqlClient.SqlConnection&gt; OpenConnectionForKeyAsync(!TKey key, string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.OpenConnectionForKeyAsync(`0,System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionForKeyAsync (key As TKey, connectionString As String, options As ConnectionOptions) As Task(Of SqlConnection)" />
      <MemberSignature Language="F#" Value="override this.OpenConnectionForKeyAsync : 'Key * string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions -&gt; System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;" Usage="rangeShardMap.OpenConnectionForKeyAsync (key, connectionString, options)" />
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
            使用状況以外のすべてのエラーは返されたタスクによって伝達されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SplitMapping">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;&gt; SplitMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; existingMapping, TKey splitAt);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt;&gt; SplitMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; existingMapping, !TKey splitAt) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.SplitMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0},`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function SplitMapping (existingMapping As RangeMapping(Of TKey), splitAt As TKey) As IReadOnlyList(Of RangeMapping(Of TKey))" />
      <MemberSignature Language="F#" Value="member this.SplitMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; * 'Key -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;&gt;" Usage="rangeShardMap.SplitMapping (existingMapping, splitAt)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Necessary to allow different types of keys", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="existingMapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
        <Parameter Name="splitAt" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="existingMapping">既存のマッピング。</param>
        <param name="splitAt">ポイントを分割します。</param>
        <summary>
            境界として指定したキーを使用して 2 つの新しいマッピングに指定されたマッピングを分割します。 新しいマッピングは、既存のマッピングと同じシャードをポイントします。
            </summary>
        <returns>作成された 2 つの新しいマッピングの読み取り専用コレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SplitMapping">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;&gt; SplitMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; existingMapping, TKey splitAt, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt;&gt; SplitMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; existingMapping, !TKey splitAt, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.SplitMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0},`0,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="F#" Value="member this.SplitMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; * 'Key * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;&gt;" Usage="rangeShardMap.SplitMapping (existingMapping, splitAt, mappingLockToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Necessary to allow different types of keys", MessageId="0")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="2")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="existingMapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
        <Parameter Name="splitAt" Type="TKey" />
        <Parameter Name="mappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="existingMapping">既存のマッピング。</param>
        <param name="splitAt">ポイントを分割します。</param>
        <param name="mappingLockToken"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> のインスタンス。</param>
        <summary>
            境界として指定したキーを使用して 2 つの新しいマッピングに指定されたマッピングを分割します。 新しいマッピングは、既存のマッピングと同じシャードをポイントします。
            </summary>
        <returns>作成された 2 つの新しいマッピングの読み取り専用コレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetMappingForKey">
      <MemberSignature Language="C#" Value="public bool TryGetMappingForKey (TKey key, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; rangeMapping);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetMappingForKey(!TKey key, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt;&amp; rangeMapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.TryGetMappingForKey(`0,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0}@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetMappingForKey (key As TKey, ByRef rangeMapping As RangeMapping(Of TKey)) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetMappingForKey : 'Key *  -&gt; bool" Usage="rangeShardMap.TryGetMappingForKey (key, rangeMapping)" />
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
        <Parameter Name="rangeMapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="key">キーの値を入力します。</param>
        <param name="rangeMapping">マッピングには、キーの値が含まれます。</param>
        <summary>
            キーを検索しよう値し、配置に対応するマッピング<paramref name="rangeMapping" />です。
            </summary>
        <returns>
          <c>true</c>マッピングが見つかった場合、 <c>false</c>それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnlockMapping">
      <MemberSignature Language="C#" Value="public void UnlockMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UnlockMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.UnlockMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="F#" Value="member this.UnlockMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; unit" Usage="rangeShardMap.UnlockMapping mappingLockToken" />
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
      <MemberSignature Language="C#" Value="public void UnlockMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; mapping, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UnlockMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; mapping, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.UnlockMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="F#" Value="member this.UnlockMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; unit" Usage="rangeShardMap.UnlockMapping (mapping, mappingLockToken)" />
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
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; UpdateMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; currentMapping, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate update);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; UpdateMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; currentMapping, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate update) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.UpdateMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateMapping (currentMapping As RangeMapping(Of TKey), update As RangeMappingUpdate) As RangeMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.UpdateMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;" Usage="rangeShardMap.UpdateMapping (currentMapping, update)" />
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
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentMapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
        <Parameter Name="update" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate" />
      </Parameters>
      <Docs>
        <param name="currentMapping">マッピングが更新中です。</param>
        <param name="update">マッピングのプロパティを更新します。</param>
        <summary>
            更新プログラム、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1" />で提供される更新プログラムを<paramref name="update" />パラメーター。
            </summary>
        <returns>更新された情報とマッピングの新しいインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMapping">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; UpdateMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; currentMapping, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate update, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; UpdateMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; currentMapping, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate update, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1.UpdateMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;" Usage="rangeShardMap.UpdateMapping (currentMapping, update, mappingLockToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="2")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentMapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;" />
        <Parameter Name="update" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMappingUpdate" />
        <Parameter Name="mappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="currentMapping">マッピングが更新中です。</param>
        <param name="update">マッピングのプロパティを更新します。</param>
        <param name="mappingLockToken"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> のインスタンス。</param>
        <summary>
            更新プログラム、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1" />で提供される更新プログラムを<paramref name="update" />パラメーター。
            </summary>
        <returns>更新された情報とマッピングの新しいインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
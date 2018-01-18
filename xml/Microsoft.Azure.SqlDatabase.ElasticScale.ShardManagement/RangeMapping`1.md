<Type Name="RangeMapping&lt;TKey&gt;" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;">
  <TypeSignature Language="C#" Value="public sealed class RangeMapping&lt;TKey&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RangeMapping`1&lt;TKey&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RangeMapping(Of TKey)" />
  <TypeSignature Language="F#" Value="type RangeMapping&lt;'Key&gt; = class&#xA;    interface IShardProvider&lt;Range&lt;'Key&gt;&gt;&#xA;    interface IShardProvider&#xA;    interface ICloneable&lt;RangeMapping&lt;'Key&gt;&gt;&#xA;    interface IMappingInfoProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TKey" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TKey"><span data-ttu-id="6939f-101">キーの型。</span><span class="sxs-lookup"><span data-stu-id="6939f-101">Key type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="6939f-102">表すキー値の範囲の間のマッピングと<see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1.Shard" />です。</span><span class="sxs-lookup"><span data-stu-id="6939f-102">Represents a mapping between a range of key values and a <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1.Shard" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt; Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1&lt;!TKey&gt; Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As RangeMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;&#xA;override this.Clone : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;" Usage="rangeMapping.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ICloneable`1.Clone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6939f-103">インターフェイスを実装するインスタンスを複製します。</span><span class="sxs-lookup"><span data-stu-id="6939f-103">Clones the instance which implements the interface.</span></span>
            </summary>
        <returns><span data-ttu-id="6939f-104">インスタンスのクローンを作成します。</span><span class="sxs-lookup"><span data-stu-id="6939f-104">Clone of the instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="rangeMapping.Equals obj" />
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
        <param name="obj"><span data-ttu-id="6939f-105">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="6939f-105">The object to compare with the current object.</span></span></param>
        <summary>
            <span data-ttu-id="6939f-106">指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="6939f-106">Determines whether the specified object is equal to the current object.</span></span>
            </summary>
        <returns><span data-ttu-id="6939f-107">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="6939f-107">True if the specified object is equal to the current object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="rangeMapping.GetHashCode " />
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
            <span data-ttu-id="6939f-108">このインスタンスのハッシュ コードを計算します。</span><span class="sxs-lookup"><span data-stu-id="6939f-108">Calculates the hash code for this instance.</span></span>
            </summary>
        <returns><span data-ttu-id="6939f-109">オブジェクトのハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="6939f-109">Hash code for the object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Shard">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard Shard { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard Shard" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1.Shard" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Shard As Shard" />
      <MemberSignature Language="F#" Value="member this.Shard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;.Shard" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6939f-110">値の範囲を含むシャードを取得します。</span><span class="sxs-lookup"><span data-stu-id="6939f-110">Gets Shard that contains the range of values.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As MappingStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6939f-111">取得、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus" />マッピングのです。</span><span class="sxs-lookup"><span data-stu-id="6939f-111">Gets the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingStatus" /> of the mapping.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="rangeMapping.ToString " />
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
            <span data-ttu-id="6939f-112">オブジェクトを文字列形式に変換します。</span><span class="sxs-lookup"><span data-stu-id="6939f-112">Converts the object to its string representation.</span></span>
            </summary>
        <returns><span data-ttu-id="6939f-113">オブジェクトの文字列表現。</span><span class="sxs-lookup"><span data-stu-id="6939f-113">String representation of the object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt; Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1&lt;!TKey&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping`1.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As Range(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.Value : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt;" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeMapping&lt;'Key&gt;.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6939f-114">マッピングの範囲を取得します。</span><span class="sxs-lookup"><span data-stu-id="6939f-114">Gets the Range of the mapping.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
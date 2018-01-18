<Type Name="Undefined" FullName="Microsoft.Azure.Documents.Undefined">
  <TypeSignature Language="C#" Value="public sealed class Undefined : IEquatable&lt;Microsoft.Azure.Documents.Undefined&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Undefined extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Undefined&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Undefined" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Undefined&#xA;Implements IEquatable(Of Undefined)" />
  <TypeSignature Language="F#" Value="type Undefined = class&#xA;    interface IEquatable&lt;Undefined&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Undefined&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="f42fc-101">クラスのインスタンスは存在しない場合は、値を示すためにパーティション キー値の一部として渡すことが Azure Cosmos DB のドキュメントにします。</span><span class="sxs-lookup"><span data-stu-id="f42fc-101">Instance of the class can be supplied as part of Partition Key Value to denote a value which is absent in the Azure Cosmos DB document.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Undefined other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Undefined other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Undefined.Equals(Microsoft.Azure.Documents.Undefined)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Undefined) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Undefined -&gt; bool" Usage="undefined.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Undefined" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="f42fc-102">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f42fc-102">The object to compare with the current object.</span></span> </param>
        <summary>
            <span data-ttu-id="f42fc-103">決定するかどうか<paramref name="other" />は<see cref="T:Microsoft.Azure.Documents.Undefined" />Cosmos DB の Azure サービスからです。</span><span class="sxs-lookup"><span data-stu-id="f42fc-103">Determines whether <paramref name="other" /> is <see cref="T:Microsoft.Azure.Documents.Undefined" /> from the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42fc-104">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="f42fc-104">true if the specified object is equal to the current object; otherwise, false.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Undefined.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (other As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="undefined.Equals other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="f42fc-105">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f42fc-105">The object to compare with the current object.</span></span> </param>
        <summary>
            <span data-ttu-id="f42fc-106">もう 1 つはあるかどうかを判断<see cref="T:Microsoft.Azure.Documents.Undefined" />Cosmos DB の Azure サービスからです。</span><span class="sxs-lookup"><span data-stu-id="f42fc-106">Determines whether other is <see cref="T:Microsoft.Azure.Documents.Undefined" /> from the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42fc-107">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="f42fc-107">true if the specified object is equal to the current object; otherwise, false.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Undefined.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="undefined.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f42fc-108">ハッシュ関数として機能、 <see cref="T:Microsoft.Azure.Documents.Undefined" /> Azure Cosmos DB データベースの種類。</span><span class="sxs-lookup"><span data-stu-id="f42fc-108">Serves as a hash function for the <see cref="T:Microsoft.Azure.Documents.Undefined" /> Azure Cosmos DB database type.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f42fc-109">ハッシュ コード値。</span><span class="sxs-lookup"><span data-stu-id="f42fc-109">A hash code value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Documents.Undefined Value;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Documents.Undefined Value" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.Undefined.Value" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Value As Undefined " />
      <MemberSignature Language="F#" Value=" staticval mutable Value : Microsoft.Azure.Documents.Undefined" Usage="Microsoft.Azure.Documents.Undefined.Value" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Undefined</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <span data-ttu-id="f42fc-110"><see cref="T:Microsoft.Azure.Documents.Undefined" />オブジェクトを再利用を支援するシングルトンです。</span><span class="sxs-lookup"><span data-stu-id="f42fc-110"><see cref="T:Microsoft.Azure.Documents.Undefined" /> singleton to help reuse the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
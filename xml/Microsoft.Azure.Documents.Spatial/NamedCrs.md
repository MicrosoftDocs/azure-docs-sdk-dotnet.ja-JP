<Type Name="NamedCrs" FullName="Microsoft.Azure.Documents.Spatial.NamedCrs">
  <TypeSignature Language="C#" Value="public sealed class NamedCrs : Microsoft.Azure.Documents.Spatial.Crs, IEquatable&lt;Microsoft.Azure.Documents.Spatial.NamedCrs&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamedCrs extends Microsoft.Azure.Documents.Spatial.Crs implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Spatial.NamedCrs&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.NamedCrs" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamedCrs&#xA;Inherits Crs&#xA;Implements IEquatable(Of NamedCrs)" />
  <TypeSignature Language="F#" Value="type NamedCrs = class&#xA;    inherit Crs&#xA;    interface IEquatable&lt;NamedCrs&gt;" />
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
    <BaseTypeName>Microsoft.Azure.Documents.Spatial.Crs</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Spatial.NamedCrs&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="36198-101">Azure Cosmos DB サービスの名前によって識別される参照システムを調整します。</span><span class="sxs-lookup"><span data-stu-id="36198-101">Coordinate Reference System which is identified by name in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Spatial.NamedCrs other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Spatial.NamedCrs other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.NamedCrs.Equals(Microsoft.Azure.Documents.Spatial.NamedCrs)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As NamedCrs) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Spatial.NamedCrs -&gt; bool" Usage="namedCrs.Equals other" />
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
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Spatial.NamedCrs" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="36198-102">この CRS と比較する CRS です。</span><span class="sxs-lookup"><span data-stu-id="36198-102">CRS to compare to this CRS.</span></span></param>
        <summary>
            <span data-ttu-id="36198-103">この CRS と等しいかどうかを<paramref name="other" />Cosmos DB の Azure サービスで CR です。</span><span class="sxs-lookup"><span data-stu-id="36198-103">Determines if this CRS is equal to <paramref name="other" /> CRS in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="36198-104"><c>true</c> CRSs が等しい場合は。</span><span class="sxs-lookup"><span data-stu-id="36198-104"><c>true</c> if CRSs are equal.</span></span> <span data-ttu-id="36198-105"><c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="36198-105"><c>false</c> otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.NamedCrs.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="namedCrs.Equals obj" />
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
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="36198-106">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="36198-106">The object to compare with the current object.</span></span> </param>
        <summary>
            <span data-ttu-id="36198-107">決定するかどうか、指定した<see cref="T:Microsoft.Azure.Documents.Spatial.NamedCrs" />が現在と等しい<see cref="T:Microsoft.Azure.Documents.Spatial.NamedCrs" />Cosmos DB の Azure サービスで。</span><span class="sxs-lookup"><span data-stu-id="36198-107">Determines whether the specified <see cref="T:Microsoft.Azure.Documents.Spatial.NamedCrs" /> is equal to the current <see cref="T:Microsoft.Azure.Documents.Spatial.NamedCrs" /> in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36198-108">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="36198-108">true if the specified object  is equal to the current object; otherwise, false.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.NamedCrs.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="namedCrs.GetHashCode " />
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
            <span data-ttu-id="36198-109">Azure Cosmos DB サービスの座標参照システムを識別する名前のハッシュ関数として機能します。</span><span class="sxs-lookup"><span data-stu-id="36198-109">Serves as a hash function for the name identifying a coordinate reference system in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36198-110">現在の <see cref="T:Microsoft.Azure.Documents.Spatial.NamedCrs" /> のハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="36198-110">A hash code for the current <see cref="T:Microsoft.Azure.Documents.Spatial.NamedCrs" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.NamedCrs.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Documents.Spatial.NamedCrs.Name" />
      <MemberType>Property</MemberType>
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36198-111">Azure Cosmos DB サービスの座標参照システムを識別する名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="36198-111">Gets a name identifying a coordinate reference system in the Azure Cosmos DB service.</span></span> <span data-ttu-id="36198-112">たとえば"urn: ogc:def:crs:OGC:1.3:CRS84"です。</span><span class="sxs-lookup"><span data-stu-id="36198-112">For example "urn:ogc:def:crs:OGC:1.3:CRS84".</span></span>
            </summary>
        <value>
            <span data-ttu-id="36198-113">座標参照システムを識別する名前です。</span><span class="sxs-lookup"><span data-stu-id="36198-113">Name identifying a coordinate reference system.</span></span> <span data-ttu-id="36198-114">たとえば"urn: ogc:def:crs:OGC:1.3:CRS84"です。</span><span class="sxs-lookup"><span data-stu-id="36198-114">For example "urn:ogc:def:crs:OGC:1.3:CRS84".</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
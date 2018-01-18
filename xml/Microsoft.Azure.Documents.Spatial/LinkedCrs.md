<Type Name="LinkedCrs" FullName="Microsoft.Azure.Documents.Spatial.LinkedCrs">
  <TypeSignature Language="C#" Value="public sealed class LinkedCrs : Microsoft.Azure.Documents.Spatial.Crs, IEquatable&lt;Microsoft.Azure.Documents.Spatial.LinkedCrs&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit LinkedCrs extends Microsoft.Azure.Documents.Spatial.Crs implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Spatial.LinkedCrs&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LinkedCrs&#xA;Inherits Crs&#xA;Implements IEquatable(Of LinkedCrs)" />
  <TypeSignature Language="F#" Value="type LinkedCrs = class&#xA;    inherit Crs&#xA;    interface IEquatable&lt;LinkedCrs&gt;" />
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
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Spatial.LinkedCrs&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="0e553-101">Azure Cosmos DB サービスのリンクで識別される参照システムを調整します。</span><span class="sxs-lookup"><span data-stu-id="0e553-101">Coordinate Reference System which is identified by link in the Azure Cosmos DB service.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Spatial.LinkedCrs other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Spatial.LinkedCrs other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LinkedCrs.Equals(Microsoft.Azure.Documents.Spatial.LinkedCrs)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As LinkedCrs) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Spatial.LinkedCrs -&gt; bool" Usage="linkedCrs.Equals other" />
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
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Spatial.LinkedCrs" />
      </Parameters>
      <Docs>
        <param name="other">
          <span data-ttu-id="0e553-102"><see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" />これと比較する<see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" />です。</span><span class="sxs-lookup"><span data-stu-id="0e553-102"><see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" /> to compare to this <see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" />.</span></span></param>
        <summary>
            <span data-ttu-id="0e553-103">かどうかをこの<see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" />と等しい<paramref name="other" />Cosmos DB の Azure サービスにします。</span><span class="sxs-lookup"><span data-stu-id="0e553-103">Determines if this <see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" /> is equal to <paramref name="other" /> in the Azure Cosmos DB service.</span></span> 
            </summary>
        <returns>
          <span data-ttu-id="0e553-104"><c>true</c> CRSs が等しい場合は。</span><span class="sxs-lookup"><span data-stu-id="0e553-104"><c>true</c> if CRSs are equal.</span></span> <span data-ttu-id="0e553-105"><c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="0e553-105"><c>false</c> otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LinkedCrs.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="linkedCrs.Equals obj" />
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
        <param name="obj"><span data-ttu-id="0e553-106">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0e553-106">The object to compare with the current object.</span></span> </param>
        <summary>
            <span data-ttu-id="0e553-107">決定するかどうか、指定した<see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" />が現在と等しい<see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" />Cosmos DB の Azure サービスで。</span><span class="sxs-lookup"><span data-stu-id="0e553-107">Determines whether the specified <see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" /> is equal to the current <see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" /> in the Azure Cosmos DB service.</span></span> 
            </summary>
        <returns>
            <span data-ttu-id="0e553-108">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="0e553-108">true if the specified object  is equal to the current object; otherwise, false.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LinkedCrs.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="linkedCrs.GetHashCode " />
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
            <span data-ttu-id="0e553-109">ハッシュ関数として機能<see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" />Cosmos DB の Azure サービスにします。</span><span class="sxs-lookup"><span data-stu-id="0e553-109">Serves as a hash function for <see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" /> in the Azure Cosmos DB service.</span></span> 
            </summary>
        <returns>
            <span data-ttu-id="0e553-110">現在の <see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" /> のハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="0e553-110">A hash code for the current <see cref="T:Microsoft.Azure.Documents.Spatial.LinkedCrs" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Href">
      <MemberSignature Language="C#" Value="public string Href { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Href" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.LinkedCrs.Href" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Href As String" />
      <MemberSignature Language="F#" Value="member this.Href : string" Usage="Microsoft.Azure.Documents.Spatial.LinkedCrs.Href" />
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
            <span data-ttu-id="0e553-111">Cosmos DB の Azure サービスで調整参照システムを識別するリンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="0e553-111">Gets the link which identifies the Coordinate Reference System in the Azure Cosmos DB service.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="0e553-112">調整参照システムを識別するリンクです。</span><span class="sxs-lookup"><span data-stu-id="0e553-112">Link which identifies the Coordinate Reference System.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HrefType">
      <MemberSignature Language="C#" Value="public string HrefType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HrefType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.LinkedCrs.HrefType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HrefType As String" />
      <MemberSignature Language="F#" Value="member this.HrefType : string" Usage="Microsoft.Azure.Documents.Spatial.LinkedCrs.HrefType" />
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
            <span data-ttu-id="0e553-113">指定された CRS パラメーターを表すために使用される形式にするヒントの省略可能な文字列を取得<see cref="P:Microsoft.Azure.Documents.Spatial.LinkedCrs.Href" />Cosmos DB の Azure サービスにします。</span><span class="sxs-lookup"><span data-stu-id="0e553-113">Gets optional string which hints at the format used to represent CRS parameters at the provided <see cref="P:Microsoft.Azure.Documents.Spatial.LinkedCrs.Href" /> in the Azure Cosmos DB service.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="0e553-114">ヒントで指定された CRS パラメーターを表すために使用される形式にする省略可能な文字列<see cref="P:Microsoft.Azure.Documents.Spatial.LinkedCrs.Href" />です。</span><span class="sxs-lookup"><span data-stu-id="0e553-114">Optional string which hints at the format used to represent CRS parameters at the provided <see cref="P:Microsoft.Azure.Documents.Spatial.LinkedCrs.Href" />.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
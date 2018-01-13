<Type Name="Property" FullName="Microsoft.Azure.Graphs.Elements.Property">
  <TypeSignature Language="C#" Value="public sealed class Property : IEquatable&lt;Microsoft.Azure.Graphs.Elements.Property&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Property extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.Graphs.Elements.Property&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.Elements.Property" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Property&#xA;Implements IEquatable(Of Property)" />
  <TypeSignature Language="F#" Value="type Property = class&#xA;    interface IEquatable&lt;Property&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
    <AssemblyVersion>1.14.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Graphs.Elements.Property&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Graphs.Elements.PropertyConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="7c7c9-101">プロパティのストレージ コンテナーです。</span><span class="sxs-lookup"><span data-stu-id="7c7c9-101">Storage container for a property.</span></span>
            <span data-ttu-id="7c7c9-102">GraphSON 形式から逆シリアル化をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="7c7c9-102">Supports deserialization from GraphSON format.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Graphs.Elements.Property other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Graphs.Elements.Property other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Property.Equals(Microsoft.Azure.Graphs.Elements.Property)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Property) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Graphs.Elements.Property -&gt; bool" Usage="property.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Graphs.Elements.Property" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="7c7c9-103">このオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7c7c9-103">An object to compare with this object.</span></span></param>
        <summary>
            <span data-ttu-id="7c7c9-104">現在のオブジェクトが、同じ型の別のオブジェクトと等しいかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="7c7c9-104">Indicates whether the current object is equal to another object of the same type.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7c7c9-105">現在のオブジェクトが <paramref name="other" /> パラメーターと等しい場合は true。それ以外の場合は false。</span><span class="sxs-lookup"><span data-stu-id="7c7c9-105">true if the current object is equal to the <paramref name="other" /> parameter; otherwise, false.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public string Key { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Property.Key" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string" Usage="Microsoft.Azure.Graphs.Elements.Property.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c7c9-106">取得またはキーを設定します。</span><span class="sxs-lookup"><span data-stu-id="7c7c9-106">Gets or sets the key.</span></span>
            </summary>
        <value>
            <span data-ttu-id="7c7c9-107">キー。</span><span class="sxs-lookup"><span data-stu-id="7c7c9-107">The key.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Property.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Sub Validate ()" />
      <MemberSignature Language="F#" Value="member this.Validate : unit -&gt; unit" Usage="property.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7c7c9-108">このインスタンスを検証します。</span><span class="sxs-lookup"><span data-stu-id="7c7c9-108">Validates this instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="7c7c9-109">プロパティの有効なキーが必要です。</span><span class="sxs-lookup"><span data-stu-id="7c7c9-109">Property must have a valid Key.</span></span>
            <span data-ttu-id="7c7c9-110">または、プロパティが有効な値を持つ必要があります。</span><span class="sxs-lookup"><span data-stu-id="7c7c9-110">or Property must have a valid Value.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public object Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Property.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As Object" />
      <MemberSignature Language="F#" Value="member this.Value : obj" Usage="Microsoft.Azure.Graphs.Elements.Property.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c7c9-111">取得または値を設定します。</span><span class="sxs-lookup"><span data-stu-id="7c7c9-111">Gets or sets the value.</span></span>
            </summary>
        <value>
            <span data-ttu-id="7c7c9-112">値。</span><span class="sxs-lookup"><span data-stu-id="7c7c9-112">The value.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
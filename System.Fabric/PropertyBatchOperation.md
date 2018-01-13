<Type Name="PropertyBatchOperation" FullName="System.Fabric.PropertyBatchOperation">
  <TypeSignature Language="C#" Value="public abstract class PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit PropertyBatchOperation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type PropertyBatchOperation = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.CheckExistsPropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.CheckSequencePropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.CheckValuePropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.DeletePropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.GetPropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.PutCustomPropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.PutPropertyOperation))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="4b1ef-101">プロパティをバッチに配置できるおよび操作を使用して報告の基本クラスを表す、<see cref="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation},System.TimeSpan,System.Threading.CancellationToken)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="4b1ef-101">Represents the base class for property operations that can be put into a batch and be submitted through the <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation},System.TimeSpan,System.Threading.CancellationToken)" /> method.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="4b1ef-102">注意してください。 1 つ<see cref="T:System.Fabric.PropertyBatchOperation" />オブジェクトが失敗し、バッチ全体が失敗し、コミットすることはできません。</span><span class="sxs-lookup"><span data-stu-id="4b1ef-102">Note that if one <see cref="T:System.Fabric.PropertyBatchOperation" /> object fails, the entire batch fails and cannot be committed.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected PropertyBatchOperation ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PropertyBatchOperation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="4b1ef-103"><see cref="T:System.Fabric.PropertyBatchOperation" /> オブジェクトの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4b1ef-103">Initializes a new instance of the <see cref="T:System.Fabric.PropertyBatchOperation" /> object.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected PropertyBatchOperation (string propertyName, System.Fabric.PropertyBatchOperationKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string propertyName, valuetype System.Fabric.PropertyBatchOperationKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PropertyBatchOperation.#ctor(System.String,System.Fabric.PropertyBatchOperationKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (propertyName As String, kind As PropertyBatchOperationKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PropertyBatchOperation : string * System.Fabric.PropertyBatchOperationKind -&gt; System.Fabric.PropertyBatchOperation" Usage="new System.Fabric.PropertyBatchOperation (propertyName, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="kind" Type="System.Fabric.PropertyBatchOperationKind" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="4b1ef-104">プロパティの文字列名。</span><span class="sxs-lookup"><span data-stu-id="4b1ef-104">String name of the Property.</span></span></para>
        </param>
        <param name="kind">
          <para>
            <span data-ttu-id="4b1ef-105"><see cref="T:System.Fabric.PropertyBatchOperationKind" />種類定義の<see cref="T:System.Fabric.PropertyBatchOperation" />です。</span><span class="sxs-lookup"><span data-stu-id="4b1ef-105"><see cref="T:System.Fabric.PropertyBatchOperationKind" /> defines the kind of the <see cref="T:System.Fabric.PropertyBatchOperation" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4b1ef-106">新しいインスタンスを初期化、<see cref="T:System.Fabric.PropertyBatchOperation" />指定したプロパティの名前と種類を持つオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4b1ef-106">Initializes a new instance of the <see cref="T:System.Fabric.PropertyBatchOperation" /> object with the specified property name and kind.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.PropertyBatchOperationKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PropertyBatchOperationKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyBatchOperation.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As PropertyBatchOperationKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.PropertyBatchOperationKind" Usage="System.Fabric.PropertyBatchOperation.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PropertyBatchOperationKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="4b1ef-107">取得、<see cref="T:System.Fabric.PropertyBatchOperationKind" />種類を示すの<see cref="T:System.Fabric.PropertyBatchOperation" />します。</span><span class="sxs-lookup"><span data-stu-id="4b1ef-107">Gets the <see cref="T:System.Fabric.PropertyBatchOperationKind" /> that indicates the kind of the <see cref="T:System.Fabric.PropertyBatchOperation" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4b1ef-108"><see cref="T:System.Fabric.PropertyBatchOperationKind" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="4b1ef-108">Returns <see cref="T:System.Fabric.PropertyBatchOperationKind" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="4b1ef-109">すべての Service Fabric の列挙には、予約済み「無効」フィールドがあります。</span><span class="sxs-lookup"><span data-stu-id="4b1ef-109">All Service Fabric enumerations have a reserved "Invalid" field.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyName">
      <MemberSignature Language="C#" Value="public string PropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PropertyName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyBatchOperation.PropertyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyName As String" />
      <MemberSignature Language="F#" Value="member this.PropertyName : string" Usage="System.Fabric.PropertyBatchOperation.PropertyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="4b1ef-110">プロパティの名前を示すこの<see cref="T:System.Fabric.PropertyBatchOperation" />にアクセスします。</span><span class="sxs-lookup"><span data-stu-id="4b1ef-110">Indicates the name of the property that this <see cref="T:System.Fabric.PropertyBatchOperation" /> accesses.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4b1ef-111"><see cref="T:System.String" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="4b1ef-111">Returns <see cref="T:System.String" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
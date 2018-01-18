<Type Name="PutCustomPropertyOperation" FullName="System.Fabric.PutCustomPropertyOperation">
  <TypeSignature Language="C#" Value="public sealed class PutCustomPropertyOperation : System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PutCustomPropertyOperation extends System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PutCustomPropertyOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PutCustomPropertyOperation&#xA;Inherits PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type PutCustomPropertyOperation = class&#xA;    inherit PropertyBatchOperation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.PropertyBatchOperation</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="5e7fc-101">指定の名前で指定したプロパティを表し、プロパティの値のカスタムの解釈のカスタムの型情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-101">Represents the specified property under the specified name and sets the custom type information for custom interpretation of the property value.</span></span></para>
    </summary>
    <remarks>
            <span data-ttu-id="5e7fc-102">カスタムの型は、Service Fabric では処理されませんが、ユーザーがカスタム型のオブジェクトをシリアル化/逆シリアル化するために使用する情報です。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-102">The custom type is information that is not processed by Service Fabric, but can be used by user to serialize/deserialize custom type objects.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutCustomPropertyOperation (string propertyName, byte[] value, string customTypeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, unsigned int8[] value, string customTypeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutCustomPropertyOperation.#ctor(System.String,System.Byte[],System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Byte(), customTypeId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutCustomPropertyOperation : string * byte[] * string -&gt; System.Fabric.PutCustomPropertyOperation" Usage="new System.Fabric.PutCustomPropertyOperation (propertyName, value, customTypeId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customTypeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="5e7fc-103">プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-103">The name of the property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="5e7fc-104">プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-104">The value for the property.</span></span></para>
        </param>
        <param name="customTypeId">
          <para><span data-ttu-id="5e7fc-105">ユーザーは、カスタムの型を定義します。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-105">The user defined custom type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5e7fc-106">新しいインスタンスを初期化、<see cref="T:System.Fabric.PutCustomPropertyOperation" />指定したプロパティ名とバイトの値、およびカスタムを適宜入力セットを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-106">Initializes a new instance of the <see cref="T:System.Fabric.PutCustomPropertyOperation" /> class with the specified property name and byte[] value, and sets the custom type accordingly.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutCustomPropertyOperation (string propertyName, double value, string customTypeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, float64 value, string customTypeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutCustomPropertyOperation.#ctor(System.String,System.Double,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Double, customTypeId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutCustomPropertyOperation : string * double * string -&gt; System.Fabric.PutCustomPropertyOperation" Usage="new System.Fabric.PutCustomPropertyOperation (propertyName, value, customTypeId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
        <Parameter Name="customTypeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="5e7fc-107">プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-107">The name of the property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="5e7fc-108">プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-108">The value for the property.</span></span></para>
        </param>
        <param name="customTypeId">
          <para><span data-ttu-id="5e7fc-109">ユーザーは、カスタムの型を定義します。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-109">The user defined custom type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5e7fc-110">新しいインスタンスを初期化、<see cref="T:System.Fabric.PutCustomPropertyOperation" />指定したプロパティ名と倍精度浮動小数点値、およびカスタムを適宜入力セットを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-110">Initializes a new instance of the <see cref="T:System.Fabric.PutCustomPropertyOperation" /> class with the specified property name and double value, and sets the custom type accordingly.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutCustomPropertyOperation (string propertyName, Guid value, string customTypeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, valuetype System.Guid value, string customTypeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutCustomPropertyOperation.#ctor(System.String,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Guid, customTypeId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutCustomPropertyOperation : string * Guid * string -&gt; System.Fabric.PutCustomPropertyOperation" Usage="new System.Fabric.PutCustomPropertyOperation (propertyName, value, customTypeId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Guid" />
        <Parameter Name="customTypeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="5e7fc-111">プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-111">The name of the property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="5e7fc-112">プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-112">The value for the property.</span></span></para>
        </param>
        <param name="customTypeId">
          <para><span data-ttu-id="5e7fc-113">ユーザーは、カスタムの型を定義します。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-113">The user defined custom type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5e7fc-114">新しいインスタンスを初期化、<see cref="T:System.Fabric.PutCustomPropertyOperation" />指定したプロパティ名と GUID の値、およびカスタムを適宜入力セットを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-114">Initializes a new instance of the <see cref="T:System.Fabric.PutCustomPropertyOperation" /> class with the specified property name and GUID value, and sets the custom type accordingly.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutCustomPropertyOperation (string propertyName, long value, string customTypeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, int64 value, string customTypeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutCustomPropertyOperation.#ctor(System.String,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Long, customTypeId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutCustomPropertyOperation : string * int64 * string -&gt; System.Fabric.PutCustomPropertyOperation" Usage="new System.Fabric.PutCustomPropertyOperation (propertyName, value, customTypeId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Int64" />
        <Parameter Name="customTypeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="5e7fc-115">プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-115">The name of the property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="5e7fc-116">プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-116">The value for the property.</span></span></para>
        </param>
        <param name="customTypeId">
          <para><span data-ttu-id="5e7fc-117">ユーザーは、カスタムの型を定義します。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-117">The user defined custom type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5e7fc-118">新しいインスタンスを初期化、<see cref="T:System.Fabric.PutCustomPropertyOperation" />指定したプロパティ名と Int64 の値、およびカスタムを適宜入力セットを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-118">Initializes a new instance of the <see cref="T:System.Fabric.PutCustomPropertyOperation" /> class with the specified property name and Int64 value, and sets the custom type accordingly.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutCustomPropertyOperation (string propertyName, string value, string customTypeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, string value, string customTypeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutCustomPropertyOperation.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As String, customTypeId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutCustomPropertyOperation : string * string * string -&gt; System.Fabric.PutCustomPropertyOperation" Usage="new System.Fabric.PutCustomPropertyOperation (propertyName, value, customTypeId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="customTypeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="5e7fc-119">プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-119">The name of the property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="5e7fc-120">プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-120">The value for the property.</span></span></para>
        </param>
        <param name="customTypeId">
          <para><span data-ttu-id="5e7fc-121">ユーザーは、カスタムの型を定義します。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-121">The user defined custom type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5e7fc-122">新しいインスタンスを初期化、<see cref="T:System.Fabric.PutCustomPropertyOperation" />指定したプロパティ名と文字列の値、およびカスタムを適宜入力セットを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-122">Initializes a new instance of the <see cref="T:System.Fabric.PutCustomPropertyOperation" /> class with the specified property name and string value, and sets the custom type accordingly.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomTypeId">
      <MemberSignature Language="C#" Value="public string CustomTypeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomTypeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PutCustomPropertyOperation.CustomTypeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomTypeId As String" />
      <MemberSignature Language="F#" Value="member this.CustomTypeId : string" Usage="System.Fabric.PutCustomPropertyOperation.CustomTypeId" />
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
          <para><span data-ttu-id="5e7fc-123">カスタム型の情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-123">Gets the custom type information.</span></span> <span data-ttu-id="5e7fc-124">この情報は、シリアル化/非 serialize カスタム型のオブジェクトへのユーザーが使用できます。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-124">This information can be used by users to serialize/de-serialize custom type objects.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5e7fc-125">カスタム型の情報です。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-125">The custom type information.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyType">
      <MemberSignature Language="C#" Value="public System.Fabric.PropertyTypeId PropertyType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PropertyTypeId PropertyType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PutCustomPropertyOperation.PropertyType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyType As PropertyTypeId" />
      <MemberSignature Language="F#" Value="member this.PropertyType : System.Fabric.PropertyTypeId" Usage="System.Fabric.PutCustomPropertyOperation.PropertyType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PropertyTypeId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5e7fc-126">プロパティの型を取得します。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-126">Gets the property type.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5e7fc-127">プロパティの型。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-127">The property type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyValue">
      <MemberSignature Language="C#" Value="public object PropertyValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object PropertyValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PutCustomPropertyOperation.PropertyValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyValue As Object" />
      <MemberSignature Language="F#" Value="member this.PropertyValue : obj" Usage="System.Fabric.PutCustomPropertyOperation.PropertyValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5e7fc-128">プロパティの値を取得します。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-128">Gets the property value.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5e7fc-129">プロパティ値。</span><span class="sxs-lookup"><span data-stu-id="5e7fc-129">The property value.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="ConditionalValue&lt;TValue&gt;" FullName="Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;">
  <TypeSignature Language="C#" Value="public struct ConditionalValue&lt;TValue&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi sealed beforefieldinit ConditionalValue`1&lt;TValue&gt; extends System.ValueType" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.ConditionalValue`1" />
  <TypeSignature Language="VB.NET" Value="Public Structure ConditionalValue(Of TValue)" />
  <TypeSignature Language="F#" Value="type ConditionalValue&lt;'Value&gt; = struct" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TValue" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TValue"><span data-ttu-id="d507c-101">これによって返される値の型<cref name="ConditionalValue{TValue}" />です。</span><span class="sxs-lookup"><span data-stu-id="d507c-101">The type of the value returned by this <cref name="ConditionalValue{TValue}" />.</span></span></typeparam>
    <summary>
            <span data-ttu-id="d507c-102">信頼性の高いコレクションしたりする Api を可能性があります値を返さない可能性がありますから返される結果のクラスです。</span><span class="sxs-lookup"><span data-stu-id="d507c-102">Result class returned by Reliable Collections APIs that may or may not return a value.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConditionalValue (bool hasValue, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool hasValue, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ConditionalValue`1.#ctor(System.Boolean,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hasValue As Boolean, value As TValue)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt; : bool * 'Value -&gt; Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;" Usage="new Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt; (hasValue, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hasValue" Type="System.Boolean" />
        <Parameter Name="value" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="hasValue"><span data-ttu-id="d507c-103">値が有効かどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="d507c-103">Indicates whether the value is valid.</span></span></param>
        <param name="value"><span data-ttu-id="d507c-104">値。</span><span class="sxs-lookup"><span data-stu-id="d507c-104">The value.</span></span></param>
        <summary>
            <span data-ttu-id="d507c-105">新しいインスタンスを初期化、<cref name="ConditionalValue{TValue}" />指定された値を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="d507c-105">Initializes a new instance of the <cref name="ConditionalValue{TValue}" /> class with the given value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasValue">
      <MemberSignature Language="C#" Value="public bool HasValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ConditionalValue`1.HasValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasValue As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasValue : bool" Usage="Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;.HasValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d507c-106">現在の <cref name="ConditionalValue{TValue}" /> オブジェクトに、基になる型の有効値があるかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="d507c-106">Gets a value indicating whether the current <cref name="ConditionalValue{TValue}" /> object has a valid value of its underlying type.</span></span>
            </summary>
        <value>
          <span data-ttu-id="d507c-107"><languageKeyword>true</languageKeyword>: 値が有効で<languageKeyword>false</languageKeyword>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="d507c-107"><languageKeyword>true</languageKeyword>: Value is valid, <languageKeyword>false</languageKeyword> otherwise.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public TValue Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TValue Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ConditionalValue`1.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As TValue" />
      <MemberSignature Language="F#" Value="member this.Value : 'Value" Usage="Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d507c-108">有効な基になる値が割り当てられているかどうか示す、<cref name="ConditionalValue{TValue}" /> の現在の値を取得します。</span><span class="sxs-lookup"><span data-stu-id="d507c-108">Gets the value of the current <cref name="ConditionalValue{TValue}" /> object if it has been assigned a valid underlying value.</span></span>
            </summary>
        <value><span data-ttu-id="d507c-109">オブジェクトの値。</span><span class="sxs-lookup"><span data-stu-id="d507c-109">The value of the object.</span></span> <span data-ttu-id="d507c-110">場合は HasValue <languageKeyword>false</languageKeyword>、TValue パラメーターの型の既定値を返します。</span><span class="sxs-lookup"><span data-stu-id="d507c-110">If HasValue is <languageKeyword>false</languageKeyword>, returns the default value for type of the TValue parameter.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
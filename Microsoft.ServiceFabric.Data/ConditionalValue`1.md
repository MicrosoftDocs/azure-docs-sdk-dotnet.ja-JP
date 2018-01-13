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
    <typeparam name="TValue">これによって返される値の型<cref name="ConditionalValue{TValue}" />です。</typeparam>
    <summary>
            信頼性の高いコレクションしたりする Api を可能性があります値を返さない可能性がありますから返される結果のクラスです。
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
        <param name="hasValue">値が有効かどうかを示します。</param>
        <param name="value">値。</param>
        <summary>
            新しいインスタンスを初期化、<cref name="ConditionalValue{TValue}" />指定された値を持つクラス。
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
            現在の <cref name="ConditionalValue{TValue}" /> オブジェクトに、基になる型の有効値があるかどうかを示す値を取得します。
            </summary>
        <value>
          <languageKeyword>true</languageKeyword>: 値が有効で<languageKeyword>false</languageKeyword>それ以外の場合。</value>
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
            有効な基になる値が割り当てられているかどうか示す、<cref name="ConditionalValue{TValue}" /> の現在の値を取得します。
            </summary>
        <value>オブジェクトの値。 場合は HasValue <languageKeyword>false</languageKeyword>、TValue パラメーターの型の既定値を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
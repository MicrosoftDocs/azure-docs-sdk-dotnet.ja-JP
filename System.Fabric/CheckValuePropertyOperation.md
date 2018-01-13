<Type Name="CheckValuePropertyOperation" FullName="System.Fabric.CheckValuePropertyOperation">
  <TypeSignature Language="C#" Value="public sealed class CheckValuePropertyOperation : System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CheckValuePropertyOperation extends System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.CheckValuePropertyOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CheckValuePropertyOperation&#xA;Inherits PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type CheckValuePropertyOperation = class&#xA;    inherit PropertyBatchOperation" />
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
      <para>表す、<see cref="T:System.Fabric.PropertyBatchOperation" />予期される値を持つプロパティの値を比較します。  </para>
    </summary>
    <remarks>
      <para>プロパティと、予期された値の値が等しくない場合、比較が失敗します。 <see cref="T:System.Fabric.CheckValuePropertyOperation" />バッチ内の書き込み操作の通常の事前条件として使用されます。 注意してください。 1 つ<see cref="T:System.Fabric.PropertyBatchOperation" />失敗した場合、バッチ全体が失敗し、コミットすることはできません。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckValuePropertyOperation (string propertyName, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckValuePropertyOperation.#ctor(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Byte())" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckValuePropertyOperation : string * byte[] -&gt; System.Fabric.CheckValuePropertyOperation" Usage="new System.Fabric.CheckValuePropertyOperation (propertyName, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.CheckValuePropertyOperation" />を持つクラスが指定された<paramref name="propertyName" />と<see cref="T:System.Byte" />の値。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckValuePropertyOperation (string propertyName, double value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, float64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckValuePropertyOperation.#ctor(System.String,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Double)" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckValuePropertyOperation : string * double -&gt; System.Fabric.CheckValuePropertyOperation" Usage="new System.Fabric.CheckValuePropertyOperation (propertyName, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.CheckValuePropertyOperation" />を持つクラスが指定された<paramref name="propertyName" />と<see cref="T:System.Double" />値。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckValuePropertyOperation (string propertyName, Guid value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, valuetype System.Guid value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckValuePropertyOperation.#ctor(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Guid)" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckValuePropertyOperation : string * Guid -&gt; System.Fabric.CheckValuePropertyOperation" Usage="new System.Fabric.CheckValuePropertyOperation (propertyName, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.CheckValuePropertyOperation" />を持つクラスが指定された<paramref name="propertyName" />と<see cref="T:System.Guid" />値。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckValuePropertyOperation (string propertyName, long value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, int64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckValuePropertyOperation.#ctor(System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Long)" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckValuePropertyOperation : string * int64 -&gt; System.Fabric.CheckValuePropertyOperation" Usage="new System.Fabric.CheckValuePropertyOperation (propertyName, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.CheckValuePropertyOperation" />を持つクラスが指定された<paramref name="propertyName" />と<see cref="T:System.Int64" />値。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckValuePropertyOperation (string propertyName, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckValuePropertyOperation.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckValuePropertyOperation : string * string -&gt; System.Fabric.CheckValuePropertyOperation" Usage="new System.Fabric.CheckValuePropertyOperation (propertyName, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.CheckValuePropertyOperation" />を持つクラスが指定された<paramref name="propertyName" />と<see cref="T:System.String" />値。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyType">
      <MemberSignature Language="C#" Value="public System.Fabric.PropertyTypeId PropertyType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PropertyTypeId PropertyType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CheckValuePropertyOperation.PropertyType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyType As PropertyTypeId" />
      <MemberSignature Language="F#" Value="member this.PropertyType : System.Fabric.PropertyTypeId" Usage="System.Fabric.CheckValuePropertyOperation.PropertyType" />
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
          <para>プロパティの型を取得します。</para>
        </summary>
        <value>
          <para>プロパティの型。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyValue">
      <MemberSignature Language="C#" Value="public object PropertyValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object PropertyValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CheckValuePropertyOperation.PropertyValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyValue As Object" />
      <MemberSignature Language="F#" Value="member this.PropertyValue : obj" Usage="System.Fabric.CheckValuePropertyOperation.PropertyValue" />
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
          <para>プロパティの値を取得します。</para>
        </summary>
        <value>
          <para>プロパティの値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
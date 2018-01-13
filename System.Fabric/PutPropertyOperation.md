<Type Name="PutPropertyOperation" FullName="System.Fabric.PutPropertyOperation">
  <TypeSignature Language="C#" Value="public sealed class PutPropertyOperation : System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PutPropertyOperation extends System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PutPropertyOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PutPropertyOperation&#xA;Inherits PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type PutPropertyOperation = class&#xA;    inherit PropertyBatchOperation" />
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
      <para>指定した名前の指定したプロパティを格納します。</para>
    </summary>
    <remarks>
      <para>注意してください。 1 つ<see cref="T:System.Fabric.PropertyBatchOperation" />失敗した場合、バッチ全体が失敗し、コミットされていません。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutPropertyOperation (string propertyName, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutPropertyOperation.#ctor(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Byte())" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutPropertyOperation : string * byte[] -&gt; System.Fabric.PutPropertyOperation" Usage="new System.Fabric.PutPropertyOperation (propertyName, value)" />
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
          <para>A<see cref="T:System.String" />プロパティの名前を定義します。</para>
        </param>
        <param name="value">
          <para>A<see cref="T:System.Byte" />プロパティの値を定義する配列。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.PutPropertyOperation" />指定したプロパティ名とバイトの値を持つクラス。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutPropertyOperation (string propertyName, double value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, float64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutPropertyOperation.#ctor(System.String,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Double)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutPropertyOperation : string * double -&gt; System.Fabric.PutPropertyOperation" Usage="new System.Fabric.PutPropertyOperation (propertyName, value)" />
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
          <para>A<see cref="T:System.String" />プロパティの名前を定義します。</para>
        </param>
        <param name="value">
          <para>A<see cref="T:System.Double" />プロパティの値を定義します。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、 <see cref="T:System.Fabric.PutPropertyOperation" /> double 型の値と指定したプロパティの名前を持つクラス。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutPropertyOperation (string propertyName, Guid value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, valuetype System.Guid value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutPropertyOperation.#ctor(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Guid)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutPropertyOperation : string * Guid -&gt; System.Fabric.PutPropertyOperation" Usage="new System.Fabric.PutPropertyOperation (propertyName, value)" />
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
          <para>A<see cref="T:System.String" />プロパティの名前を定義します。</para>
        </param>
        <param name="value">
          <para>A<see cref="T:System.Guid" />プロパティの値を定義します。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.PutPropertyOperation" />指定したプロパティ名と GUID 値を持つクラス。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutPropertyOperation (string propertyName, long value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, int64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutPropertyOperation.#ctor(System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Long)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutPropertyOperation : string * int64 -&gt; System.Fabric.PutPropertyOperation" Usage="new System.Fabric.PutPropertyOperation (propertyName, value)" />
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
          <para>A<see cref="T:System.String" />プロパティの名前を定義します。</para>
        </param>
        <param name="value">
          <para><see cref="T:System.Int64" />プロパティの値を定義します。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、 <see cref="T:System.Fabric.PutPropertyOperation" /> Int64 値と指定したプロパティの名前を持つクラス。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutPropertyOperation (string propertyName, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutPropertyOperation.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutPropertyOperation : string * string -&gt; System.Fabric.PutPropertyOperation" Usage="new System.Fabric.PutPropertyOperation (propertyName, value)" />
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
          <para>A<see cref="T:System.String" />プロパティの名前を定義します。</para>
        </param>
        <param name="value">
          <para>A<see cref="T:System.String" />プロパティの値を定義します。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.PutPropertyOperation" />指定されたプロパティ名と文字列値を持つクラス。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyType">
      <MemberSignature Language="C#" Value="public System.Fabric.PropertyTypeId PropertyType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PropertyTypeId PropertyType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PutPropertyOperation.PropertyType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyType As PropertyTypeId" />
      <MemberSignature Language="F#" Value="member this.PropertyType : System.Fabric.PropertyTypeId" Usage="System.Fabric.PutPropertyOperation.PropertyType" />
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
          <para><see cref="T:System.Fabric.PropertyTypeId" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyValue">
      <MemberSignature Language="C#" Value="public object PropertyValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object PropertyValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PutPropertyOperation.PropertyValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyValue As Object" />
      <MemberSignature Language="F#" Value="member this.PropertyValue : obj" Usage="System.Fabric.PutPropertyOperation.PropertyValue" />
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
          <para><see cref="T:System.Object" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
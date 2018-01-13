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
      <para>指定の名前で指定したプロパティを表し、プロパティの値のカスタムの解釈のカスタムの型情報を設定します。</para>
    </summary>
    <remarks>
            カスタムの型は、Service Fabric では処理されませんが、ユーザーがカスタム型のオブジェクトをシリアル化/逆シリアル化するために使用する情報です。</remarks>
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
          <para>プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <param name="customTypeId">
          <para>ユーザーは、カスタムの型を定義します。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.PutCustomPropertyOperation" />指定したプロパティ名とバイトの値、およびカスタムを適宜入力セットを持つクラス。</para>
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
          <para>プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <param name="customTypeId">
          <para>ユーザーは、カスタムの型を定義します。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.PutCustomPropertyOperation" />指定したプロパティ名と倍精度浮動小数点値、およびカスタムを適宜入力セットを持つクラス。</para>
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
          <para>プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <param name="customTypeId">
          <para>ユーザーは、カスタムの型を定義します。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.PutCustomPropertyOperation" />指定したプロパティ名と GUID の値、およびカスタムを適宜入力セットを持つクラス。</para>
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
          <para>プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <param name="customTypeId">
          <para>ユーザーは、カスタムの型を定義します。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.PutCustomPropertyOperation" />指定したプロパティ名と Int64 の値、およびカスタムを適宜入力セットを持つクラス。</para>
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
          <para>プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <param name="customTypeId">
          <para>ユーザーは、カスタムの型を定義します。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.PutCustomPropertyOperation" />指定したプロパティ名と文字列の値、およびカスタムを適宜入力セットを持つクラス。</para>
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
          <para>カスタム型の情報を取得します。 この情報は、シリアル化/非 serialize カスタム型のオブジェクトへのユーザーが使用できます。</para>
        </summary>
        <value>
          <para>カスタム型の情報です。</para>
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
          <para>プロパティの値を取得します。</para>
        </summary>
        <value>
          <para>プロパティ値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
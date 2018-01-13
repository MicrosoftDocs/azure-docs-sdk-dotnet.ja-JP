<Type Name="DataType" FullName="Microsoft.Azure.Search.Models.DataType">
  <TypeSignature Language="C#" Value="public sealed class DataType : Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.DataType&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DataType extends Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;class Microsoft.Azure.Search.Models.DataType&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DataType" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DataType&#xA;Inherits ExtensibleEnum(Of DataType)" />
  <TypeSignature Language="F#" Value="type DataType = class&#xA;    inherit ExtensibleEnum&lt;DataType&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.DataType&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Search.Models.DataType</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1&lt;Microsoft.Azure.Search.Models.DataType&gt;))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure Search インデックスには、フィールドのデータ型を定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Boolean">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType Boolean;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType Boolean" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.Boolean" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Boolean As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable Boolean : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Boolean" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            フィールドに、ブール値 (true または false) が含まれていることを示します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Collection">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataType Collection (Microsoft.Azure.Search.Models.DataType elementType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataType Collection(class Microsoft.Azure.Search.Models.DataType elementType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataType.Collection(Microsoft.Azure.Search.Models.DataType)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Collection (elementType As DataType) As DataType" />
      <MemberSignature Language="F#" Value="static member Collection : Microsoft.Azure.Search.Models.DataType -&gt; Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Collection elementType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="elementType" Type="Microsoft.Azure.Search.Models.DataType" />
      </Parameters>
      <Docs>
        <param name="elementType">コレクションの要素のデータ型です。</param>
        <summary>
            指定された型のコレクションのデータ型を作成します。
            </summary>
        <returns>コレクションの新しいデータ型です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataType Create (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataType Create(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataType.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (name As String) As DataType" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Create name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">データ型の名前です。</param>
        <summary>
            新しいデータ型インスタンスを作成または指定された名前と一致する既知のデータ型の場合は、既存のインスタンスを返します。
            </summary>
        <returns>指定した名前のデータ型のインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DateTimeOffset">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType DateTimeOffset;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType DateTimeOffset" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.DateTimeOffset" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DateTimeOffset As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable DateTimeOffset : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.DateTimeOffset" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            フィールドにタイム ゾーン情報を含む、日付/時刻値が含まれていることを示します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Double">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType Double;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType Double" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.Double" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Double As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable Double : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Double" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            フィールドに、IEEE 倍精度浮動小数点数が含まれていることを示します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeographyPoint">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType GeographyPoint;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType GeographyPoint" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.GeographyPoint" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly GeographyPoint As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable GeographyPoint : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.GeographyPoint" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            フィールドが経度と緯度の観点からは、地理的な場所が含まれていることを示します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Int32">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType Int32;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType Int32" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.Int32" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Int32 As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable Int32 : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Int32" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            フィールドが 32 ビット符号付き整数が含まれていることを示します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Int64">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType Int64;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType Int64" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.Int64" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Int64 As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable Int64 : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Int64" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            フィールドに、64 ビット符号付き整数が含まれていることを示します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator Microsoft.Azure.Search.Models.DataType (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname class Microsoft.Azure.Search.Models.DataType op_Implicit(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataType.op_Implicit(System.String)~Microsoft.Azure.Search.Models.DataType" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (name As String) As DataType" />
      <MemberSignature Language="F#" Value="static member op_Implicit : string -&gt; Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.op_Implicit name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">変換する文字列。</param>
        <summary>
            文字列からのデータ型への暗黙的な変換を定義します。
            </summary>
        <returns>データ型としての文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="String">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType String;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType String" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.String" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly String As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable String : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.String" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            フィールドに文字列が含まれていることを示します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
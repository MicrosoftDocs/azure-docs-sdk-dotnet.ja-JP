<Type Name="JsonFormat" FullName="Microsoft.Azure.Management.DataFactories.Models.JsonFormat">
  <TypeSignature Language="C#" Value="public class JsonFormat : Microsoft.Azure.Management.DataFactories.Models.StorageFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JsonFormat extends Microsoft.Azure.Management.DataFactories.Models.StorageFormat" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.JsonFormat" />
  <TypeSignature Language="VB.NET" Value="Public Class JsonFormat&#xA;Inherits StorageFormat" />
  <TypeSignature Language="F#" Value="type JsonFormat = class&#xA;    inherit StorageFormat" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.StorageFormat</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            JSON 形式で格納されているデータ。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonFormat ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncodingName">
      <MemberSignature Language="C#" Value="public string EncodingName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncodingName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.EncodingName" />
      <MemberSignature Language="VB.NET" Value="Public Property EncodingName As String" />
      <MemberSignature Language="F#" Value="member this.EncodingName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.JsonFormat.EncodingName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            使用するエンコーディングのコード ページ名。 指定しない場合、バイト順マーク (BOM) が別の Unicode エンコードを表しますしない限り、既定値は"utf-8"にします。 "Name"テーブルの列に、次の参照のエンコーディングのサポートされている値の完全な一覧が見つかりません: https://msdn.microsoft.com/library/system.text.encoding.aspx#Anchor_5 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePattern">
      <MemberSignature Language="C#" Value="public string FilePattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.FilePattern" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePattern As String" />
      <MemberSignature Language="F#" Value="member this.FilePattern : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.JsonFormat.FilePattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            JSON のファイルのパターン。 単一の JSON オブジェクトを分離する方法をより具体的になります。 いずれかを指定する必要があります<see cref="T:Microsoft.Azure.Management.DataFactories.Models.JsonFormatFilePattern" />です。
            既定値は、"setOfObjects"です。
            このコマンドは、大文字小文字を区別します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JsonNodeReference">
      <MemberSignature Language="C#" Value="public string JsonNodeReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JsonNodeReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.JsonNodeReference" />
      <MemberSignature Language="VB.NET" Value="Public Property JsonNodeReference As String" />
      <MemberSignature Language="F#" Value="member this.JsonNodeReference : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.JsonFormat.JsonNodeReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 フラット化する JSON 配列ノードの JSONPath します。 参照: http://goessner.net/articles/JsonPath/ です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JsonPathDefinition">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.Dictionary&lt;string,string&gt; JsonPathDefinition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.Dictionary`2&lt;string, string&gt; JsonPathDefinition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.JsonPathDefinition" />
      <MemberSignature Language="VB.NET" Value="Public Property JsonPathDefinition As Dictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.JsonPathDefinition : System.Collections.Generic.Dictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.JsonFormat.JsonPathDefinition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 行にオブジェクトを JSON に変換するときに、変換された行の対象となる列の元の JSON オブジェクトの相対 JSONPath の定義。 例: {"Column1":"$ です。Column1Path"}。 ルート項目の JSONPath は、「$」文字で始まらなければなりません。 JsonNodeReference によって定義されたフラット化された配列内の他のすべての項目がない必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NestingSeparator">
      <MemberSignature Language="C#" Value="public string NestingSeparator { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NestingSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.NestingSeparator" />
      <MemberSignature Language="VB.NET" Value="Public Property NestingSeparator As String" />
      <MemberSignature Language="F#" Value="member this.NestingSeparator : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.JsonFormat.NestingSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            入れ子になったレベルを区切るために使用する文字。 既定値は"です"。(ドット)。 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
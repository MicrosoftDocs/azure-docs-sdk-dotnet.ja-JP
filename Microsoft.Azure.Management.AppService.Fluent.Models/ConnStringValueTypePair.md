<Type Name="ConnStringValueTypePair" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair">
  <TypeSignature Language="C#" Value="public class ConnStringValueTypePair" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnStringValueTypePair extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnStringValueTypePair" />
  <TypeSignature Language="F#" Value="type ConnStringValueTypePair = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            接続文字列値をデータベースのペアを入力します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnStringValueTypePair ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ConnStringValueTypePair クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnStringValueTypePair (string value, Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string value, valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair.#ctor(System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As String, type As ConnectionStringType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair : string * Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair (value, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType" />
      </Parameters>
      <Docs>
        <param name="value">ペアの値です。</param>
        <param name="type">データベースの種類。 使用可能な値が含まれます: 'MySql'、'SQLServer'、'SQLAzure'、'Custom'、'NotificationHub'、'ServiceBus'、'EventHub'、'ApiHub'、'DocDb'、'RedisCache'</param>
        <summary>
            ConnStringValueTypePair クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As ConnectionStringType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータベースの種類を設定します。 使用可能な値が含まれます: 'MySql'、'SQLServer'、'SQLAzure'、'Custom'、'NotificationHub'、'ServiceBus'、'EventHub'、'ApiHub'、'DocDb'、'RedisCache'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="connStringValueTypePair.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはペアの値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
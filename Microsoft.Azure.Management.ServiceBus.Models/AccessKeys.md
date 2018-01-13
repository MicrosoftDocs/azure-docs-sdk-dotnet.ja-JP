<Type Name="AccessKeys" FullName="Microsoft.Azure.Management.ServiceBus.Models.AccessKeys">
  <TypeSignature Language="C#" Value="public class AccessKeys" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AccessKeys extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.AccessKeys" />
  <TypeSignature Language="VB.NET" Value="Public Class AccessKeys" />
  <TypeSignature Language="F#" Value="type AccessKeys = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Namespace/ServiceBus 接続文字列
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessKeys ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.AccessKeys.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AccessKeys クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessKeys (string primaryConnectionString = null, string secondaryConnectionString = null, string aliasPrimaryConnectionString = null, string aliasSecondaryConnectionString = null, string primaryKey = null, string secondaryKey = null, string keyName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string primaryConnectionString, string secondaryConnectionString, string aliasPrimaryConnectionString, string aliasSecondaryConnectionString, string primaryKey, string secondaryKey, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.AccessKeys.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional primaryConnectionString As String = null, Optional secondaryConnectionString As String = null, Optional aliasPrimaryConnectionString As String = null, Optional aliasSecondaryConnectionString As String = null, Optional primaryKey As String = null, Optional secondaryKey As String = null, Optional keyName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.AccessKeys : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.AccessKeys" Usage="new Microsoft.Azure.Management.ServiceBus.Models.AccessKeys (primaryConnectionString, secondaryConnectionString, aliasPrimaryConnectionString, aliasSecondaryConnectionString, primaryKey, secondaryKey, keyName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primaryConnectionString" Type="System.String" />
        <Parameter Name="secondaryConnectionString" Type="System.String" />
        <Parameter Name="aliasPrimaryConnectionString" Type="System.String" />
        <Parameter Name="aliasSecondaryConnectionString" Type="System.String" />
        <Parameter Name="primaryKey" Type="System.String" />
        <Parameter Name="secondaryKey" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="primaryConnectionString">作成された名前空間の承認規則のプライマリ接続文字列。</param>
        <param name="secondaryConnectionString">作成された名前空間の承認規則のセカンダリ接続文字列。</param>
        <param name="aliasPrimaryConnectionString">GEO DR が有効になっている場合、別名のプライマリ接続文字列</param>
        <param name="aliasSecondaryConnectionString">GEO DR が有効になっている場合、別名のセカンダリ接続文字列</param>
        <param name="primaryKey">SAS トークンの署名と検証用の Base64 でエンコードされた 256 ビットのプライマリ キー。</param>
        <param name="secondaryKey">SAS トークンの署名と検証用の Base64 でエンコードされた 256 ビットのプライマリ キー。</param>
        <param name="keyName">承認規則を説明する文字列。</param>
        <summary>
            AccessKeys クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AliasPrimaryConnectionString">
      <MemberSignature Language="C#" Value="public string AliasPrimaryConnectionString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AliasPrimaryConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.AccessKeys.AliasPrimaryConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AliasPrimaryConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.AliasPrimaryConnectionString : string" Usage="Microsoft.Azure.Management.ServiceBus.Models.AccessKeys.AliasPrimaryConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aliasPrimaryConnectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            GEO DR が有効になっている場合、別名のプライマリ接続文字列を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AliasSecondaryConnectionString">
      <MemberSignature Language="C#" Value="public string AliasSecondaryConnectionString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AliasSecondaryConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.AccessKeys.AliasSecondaryConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AliasSecondaryConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.AliasSecondaryConnectionString : string" Usage="Microsoft.Azure.Management.ServiceBus.Models.AccessKeys.AliasSecondaryConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aliasSecondaryConnectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            GEO DR が有効になっている場合、別名のセカンダリ接続文字列を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.AccessKeys.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string" Usage="Microsoft.Azure.Management.ServiceBus.Models.AccessKeys.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            承認規則を説明する文字列を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryConnectionString">
      <MemberSignature Language="C#" Value="public string PrimaryConnectionString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.AccessKeys.PrimaryConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryConnectionString : string" Usage="Microsoft.Azure.Management.ServiceBus.Models.AccessKeys.PrimaryConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryConnectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            作成された名前空間の承認規則のプライマリ接続文字列を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryKey">
      <MemberSignature Language="C#" Value="public string PrimaryKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.AccessKeys.PrimaryKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryKey As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryKey : string" Usage="Microsoft.Azure.Management.ServiceBus.Models.AccessKeys.PrimaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            署名と SAS トークンを検証する base64 でエンコードされた 256 ビット プライマリ キーを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryConnectionString">
      <MemberSignature Language="C#" Value="public string SecondaryConnectionString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.AccessKeys.SecondaryConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryConnectionString : string" Usage="Microsoft.Azure.Management.ServiceBus.Models.AccessKeys.SecondaryConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondaryConnectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            作成された名前空間の承認規則のセカンダリ接続文字列を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryKey">
      <MemberSignature Language="C#" Value="public string SecondaryKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.AccessKeys.SecondaryKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryKey As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryKey : string" Usage="Microsoft.Azure.Management.ServiceBus.Models.AccessKeys.SecondaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            署名と SAS トークンを検証する base64 でエンコードされた 256 ビット プライマリ キーを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
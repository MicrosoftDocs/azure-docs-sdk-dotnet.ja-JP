<Type Name="SharedKeys" FullName="Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys">
  <TypeSignature Language="C#" Value="public class SharedKeys" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedKeys extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedKeys" />
  <TypeSignature Language="F#" Value="type SharedKeys = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ワークスペースの共有キー。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedKeys ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SharedKeys クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedKeys (string primarySharedKey = null, string secondarySharedKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string primarySharedKey, string secondarySharedKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional primarySharedKey As String = null, Optional secondarySharedKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys : string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys (primarySharedKey, secondarySharedKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primarySharedKey" Type="System.String" />
        <Parameter Name="secondarySharedKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="primarySharedKey">ワークスペースの主キーを共有します。</param>
        <param name="secondarySharedKey">ワークスペースのセカンダリ キーを共有します。</param>
        <summary>
            SharedKeys クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimarySharedKey">
      <MemberSignature Language="C#" Value="public string PrimarySharedKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimarySharedKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys.PrimarySharedKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimarySharedKey As String" />
      <MemberSignature Language="F#" Value="member this.PrimarySharedKey : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys.PrimarySharedKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primarySharedKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはワークスペースの主な共有キーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondarySharedKey">
      <MemberSignature Language="C#" Value="public string SecondarySharedKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondarySharedKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys.SecondarySharedKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondarySharedKey As String" />
      <MemberSignature Language="F#" Value="member this.SecondarySharedKey : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys.SecondarySharedKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondarySharedKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはワークスペースのセカンダリの共有キーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
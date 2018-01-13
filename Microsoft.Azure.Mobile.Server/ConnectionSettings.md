<Type Name="ConnectionSettings" FullName="Microsoft.Azure.Mobile.Server.ConnectionSettings">
  <TypeSignature Language="C#" Value="public class ConnectionSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectionSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.ConnectionSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectionSettings" />
  <TypeSignature Language="F#" Value="type ConnectionSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            このクラスは、接続文字列の構成情報を提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectionSettings (string name, string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.ConnectionSettings.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.ConnectionSettings : string * string -&gt; Microsoft.Azure.Mobile.Server.ConnectionSettings" Usage="new Microsoft.Azure.Mobile.Server.ConnectionSettings (name, connectionString)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">接続文字列の設定の名前。</param>
        <param name="connectionString">実際の接続文字列。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Mobile.Server.ConnectionSettings" />と、指定された<paramref name="name" />と<paramref name="connectionString" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ConnectionSettings.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.Azure.Mobile.Server.ConnectionSettings.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または実際の接続文字列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ConnectionSettings.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Mobile.Server.ConnectionSettings.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または接続文字列の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ConnectionSettings.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.Mobile.Server.ConnectionSettings.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定するなど、この接続文字列で使用するプロバイダー <c>System.Data.SqlClient</c>です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
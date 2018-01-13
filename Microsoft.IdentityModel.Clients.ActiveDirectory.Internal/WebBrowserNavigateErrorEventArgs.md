<Type Name="WebBrowserNavigateErrorEventArgs" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs">
  <TypeSignature Language="C#" Value="public class WebBrowserNavigateErrorEventArgs : System.ComponentModel.CancelEventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebBrowserNavigateErrorEventArgs extends System.ComponentModel.CancelEventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public Class WebBrowserNavigateErrorEventArgs&#xA;Inherits CancelEventArgs" />
  <TypeSignature Language="F#" Value="type WebBrowserNavigateErrorEventArgs = class&#xA;    inherit CancelEventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ComponentModel.CancelEventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Web ブラウザーのナビゲーションに失敗したときに受信したイベント agruments を表します。
            このクラスは COM 要件に対してのみ公開されますが、開発者によっては使用できません。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebBrowserNavigateErrorEventArgs (string url, string targetFrameName, int statusCode, object webBrowserActiveXInstance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string url, string targetFrameName, int32 statusCode, object webBrowserActiveXInstance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.#ctor(System.String,System.String,System.Int32,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As String, targetFrameName As String, statusCode As Integer, webBrowserActiveXInstance As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs : string * string * int * obj -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs (url, targetFrameName, statusCode, webBrowserActiveXInstance)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="targetFrameName" Type="System.String" />
        <Parameter Name="statusCode" Type="System.Int32" />
        <Parameter Name="webBrowserActiveXInstance" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="url">url を文字列としてエラーが発生した場合無効な url があります。</param>
        <param name="targetFrameName">障害のあるターゲット フレームの名前</param>
        <param name="statusCode">エラー状態コード</param>
        <param name="webBrowserActiveXInstance">オブジェクトを返す</param>
        <summary>
            コンストラクター
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public int StatusCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusCode As Integer" />
      <MemberSignature Language="F#" Value="member this.StatusCode : int" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ADAL です。ネイティブ コードを持つ文字列に次のコードの解釈を行わないかここを実行すべきことを考慮の対象になる必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetFrameName">
      <MemberSignature Language="C#" Value="public string TargetFrameName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetFrameName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.TargetFrameName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetFrameName As String" />
      <MemberSignature Language="F#" Value="member this.TargetFrameName : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.TargetFrameName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            障害のあるターゲット フレームの名前
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            url を文字列としてエラーが発生した場合無効な url があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebBrowserActiveXInstance">
      <MemberSignature Language="C#" Value="public object WebBrowserActiveXInstance { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object WebBrowserActiveXInstance" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.WebBrowserActiveXInstance" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WebBrowserActiveXInstance As Object" />
      <MemberSignature Language="F#" Value="member this.WebBrowserActiveXInstance : obj" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.Internal.WebBrowserNavigateErrorEventArgs.WebBrowserActiveXInstance" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            オブジェクトを返す
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
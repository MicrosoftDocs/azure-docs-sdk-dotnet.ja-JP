<Type Name="MpnsTileMessage" FullName="Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage">
  <TypeSignature Language="C#" Value="public abstract class MpnsTileMessage : Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MpnsTileMessage extends Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MpnsTileMessage&#xA;Inherits MpnsMessage" />
  <TypeSignature Language="F#" Value="type MpnsTileMessage = class&#xA;    inherit MpnsMessage" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            によって使用されるすべての MPNS タイルの抽象基本クラス<see cref="T:Microsoft.Azure.Mobile.Server.MpnsPushMessage" />および関連クラスです。 
            </summary>
    <remarks>
            このクラスは、直接使用するものではありません。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MpnsTileMessage (string version, string template);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string version, string template) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (version As String, template As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage : string * string -&gt; Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage" Usage="new Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage (version, template)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="template" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="version">タイルのバージョン。</param>
        <param name="template">テンプレートの名前。</param>
        <summary>
            新しい初期化<see cref="T:Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage" />で実装が、指定された<paramref name="version" />と<paramref name="template" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または 1 ~ 99 のタイルのカウント フィールドに表示される値を設定します。 値の 0 の場合は、カウントは表示されません。 このプロパティが設定されていない場合、カウントの表示は更新中に変更されません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または省略可能な ID またはタイルを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Title">
      <MemberSignature Language="C#" Value="public string Title { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Title" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage.Title" />
      <MemberSignature Language="VB.NET" Value="Public Property Title As String" />
      <MemberSignature Language="F#" Value="member this.Title : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage.Title" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または中規模およびワイド タイルのサイズの前面に表示されるテキストを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
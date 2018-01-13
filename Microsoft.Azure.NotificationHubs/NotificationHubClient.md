<Type Name="NotificationHubClient" FullName="Microsoft.Azure.NotificationHubs.NotificationHubClient">
  <TypeSignature Language="C#" Value="public class NotificationHubClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NotificationHubClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />
  <TypeSignature Language="VB.NET" Value="Public Class NotificationHubClient" />
  <TypeSignature Language="F#" Value="type NotificationHubClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>通知ハブのクライアントを表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelNotificationAsync (string scheduledNotificationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelNotificationAsync(string scheduledNotificationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CancelNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelNotificationAsync (scheduledNotificationId As String) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelNotificationAsync : string -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.CancelNotificationAsync scheduledNotificationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scheduledNotificationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scheduledNotificationId">定期的な通知の識別子です。</param>
        <summary>
            通知を非同期的に取り消します。
            </summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAdmNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt; CreateAdmNativeRegistrationAsync (string admRegistrationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt; CreateAdmNativeRegistrationAsync(string admRegistrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAdmNativeRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAdmNativeRegistrationAsync (admRegistrationId As String) As Task(Of AdmRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAdmNativeRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt;" Usage="notificationHubClient.CreateAdmNativeRegistrationAsync admRegistrationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="admRegistrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="admRegistrationId">管理登録の識別子です。</param>
        <summary>ネイティブの管理の登録を非同期に作成します。</summary>
        <returns>非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAdmNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt; CreateAdmNativeRegistrationAsync (string admRegistrationId, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt; CreateAdmNativeRegistrationAsync(string admRegistrationId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAdmNativeRegistrationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAdmNativeRegistrationAsync (admRegistrationId As String, tags As IEnumerable(Of String)) As Task(Of AdmRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAdmNativeRegistrationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt;" Usage="notificationHubClient.CreateAdmNativeRegistrationAsync (admRegistrationId, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="admRegistrationId" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="admRegistrationId">管理登録の識別子です。</param>
        <param name="tags">登録用のタグ。</param>
        <summary>ネイティブの管理の登録を非同期に作成します。</summary>
        <returns>非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAdmTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt; CreateAdmTemplateRegistrationAsync (string admRegistrationId, string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt; CreateAdmTemplateRegistrationAsync(string admRegistrationId, string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAdmTemplateRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAdmTemplateRegistrationAsync (admRegistrationId As String, jsonPayload As String) As Task(Of AdmTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAdmTemplateRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateAdmTemplateRegistrationAsync (admRegistrationId, jsonPayload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="admRegistrationId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="admRegistrationId">管理登録の識別子です。</param>
        <param name="jsonPayload">JSON ペイロード。</param>
        <summary>管理用テンプレート登録を非同期に作成します。</summary>
        <returns>非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAdmTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt; CreateAdmTemplateRegistrationAsync (string admRegistrationId, string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt; CreateAdmTemplateRegistrationAsync(string admRegistrationId, string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAdmTemplateRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAdmTemplateRegistrationAsync (admRegistrationId As String, jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of AdmTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAdmTemplateRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateAdmTemplateRegistrationAsync (admRegistrationId, jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="admRegistrationId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="admRegistrationId">管理登録の識別子です。</param>
        <param name="jsonPayload">JSON ペイロード。</param>
        <param name="tags">タグ。</param>
        <summary>管理用テンプレート登録を非同期に作成します。</summary>
        <returns>非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAppleNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt; CreateAppleNativeRegistrationAsync (string deviceToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt; CreateAppleNativeRegistrationAsync(string deviceToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAppleNativeRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAppleNativeRegistrationAsync (deviceToken As String) As Task(Of AppleRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAppleNativeRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt;" Usage="notificationHubClient.CreateAppleNativeRegistrationAsync deviceToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceToken">デバイス トークンです。</param>
        <summary>Apple のネイティブ登録を非同期に作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAppleNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt; CreateAppleNativeRegistrationAsync (string deviceToken, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt; CreateAppleNativeRegistrationAsync(string deviceToken, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAppleNativeRegistrationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAppleNativeRegistrationAsync (deviceToken As String, tags As IEnumerable(Of String)) As Task(Of AppleRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAppleNativeRegistrationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt;" Usage="notificationHubClient.CreateAppleNativeRegistrationAsync (deviceToken, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceToken" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="deviceToken">デバイス トークンです。</param>
        <param name="tags">タグ。</param>
        <summary>Apple のネイティブ登録を非同期に作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAppleTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt; CreateAppleTemplateRegistrationAsync (string deviceToken, string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt; CreateAppleTemplateRegistrationAsync(string deviceToken, string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAppleTemplateRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAppleTemplateRegistrationAsync (deviceToken As String, jsonPayload As String) As Task(Of AppleTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAppleTemplateRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateAppleTemplateRegistrationAsync (deviceToken, jsonPayload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceToken" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceToken">デバイス トークンです。</param>
        <param name="jsonPayload">JSON ペイロード。</param>
        <summary>非同期的に、Apple のテンプレート登録を作成します。 作成時に追加のプロパティを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" />メソッドです。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAppleTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt; CreateAppleTemplateRegistrationAsync (string deviceToken, string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt; CreateAppleTemplateRegistrationAsync(string deviceToken, string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAppleTemplateRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAppleTemplateRegistrationAsync (deviceToken As String, jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of AppleTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAppleTemplateRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateAppleTemplateRegistrationAsync (deviceToken, jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceToken" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="deviceToken">デバイス トークンです。</param>
        <param name="jsonPayload">JSON ペイロード。</param>
        <param name="tags">タグ。</param>
        <summary>非同期的に、Apple のテンプレート登録を作成します。 作成時に追加のプロパティを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" />メソッドです。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBaiduNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt; CreateBaiduNativeRegistrationAsync (string userId, string channelId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt; CreateBaiduNativeRegistrationAsync(string userId, string channelId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateBaiduNativeRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBaiduNativeRegistrationAsync (userId As String, channelId As String) As Task(Of BaiduRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateBaiduNativeRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt;" Usage="notificationHubClient.CreateBaiduNativeRegistrationAsync (userId, channelId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="channelId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="userId">ユーザーの識別子です。</param>
        <param name="channelId">チャネルの識別子です。</param>
        <summary>
            非同期的に baidu ネイティブ登録を作成します。
            </summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBaiduNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt; CreateBaiduNativeRegistrationAsync (string userId, string channelId, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt; CreateBaiduNativeRegistrationAsync(string userId, string channelId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateBaiduNativeRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBaiduNativeRegistrationAsync (userId As String, channelId As String, tags As IEnumerable(Of String)) As Task(Of BaiduRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateBaiduNativeRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt;" Usage="notificationHubClient.CreateBaiduNativeRegistrationAsync (userId, channelId, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="channelId" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="userId">ユーザーの識別子です。</param>
        <param name="channelId">チャネルの識別子です。</param>
        <param name="tags">タグ。</param>
        <summary>
            非同期的に baidu ネイティブ登録を作成します。
            </summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBaiduTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt; CreateBaiduTemplateRegistrationAsync (string userId, string channelId, string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt; CreateBaiduTemplateRegistrationAsync(string userId, string channelId, string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateBaiduTemplateRegistrationAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBaiduTemplateRegistrationAsync (userId As String, channelId As String, jsonPayload As String) As Task(Of BaiduTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateBaiduTemplateRegistrationAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateBaiduTemplateRegistrationAsync (userId, channelId, jsonPayload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="channelId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="userId">ユーザーの識別子です。</param>
        <param name="channelId">チャネルの識別子です。</param>
        <param name="jsonPayload">Json ペイロード。</param>
        <summary>
            非同期的に baidu テンプレート登録を作成します。
            </summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBaiduTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt; CreateBaiduTemplateRegistrationAsync (string userId, string channelId, string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt; CreateBaiduTemplateRegistrationAsync(string userId, string channelId, string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateBaiduTemplateRegistrationAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBaiduTemplateRegistrationAsync (userId As String, channelId As String, jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of BaiduTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateBaiduTemplateRegistrationAsync : string * string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateBaiduTemplateRegistrationAsync (userId, channelId, jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="channelId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="userId">ユーザーの識別子です。</param>
        <param name="channelId">チャネルの識別子です。</param>
        <param name="jsonPayload">Json ペイロード。</param>
        <param name="tags">タグ。</param>
        <summary>
            非同期的に baidu テンプレート登録を作成します。
            </summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateClientFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.NotificationHubClient CreateClientFromConnectionString (string connectionString, string notificationHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.NotificationHubClient CreateClientFromConnectionString(string connectionString, string notificationHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateClientFromConnectionString(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateClientFromConnectionString (connectionString As String, notificationHubPath As String) As NotificationHubClient" />
      <MemberSignature Language="F#" Value="static member CreateClientFromConnectionString : string * string -&gt; Microsoft.Azure.NotificationHubs.NotificationHubClient" Usage="Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateClientFromConnectionString (connectionString, notificationHubPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="notificationHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">接続文字列。</param>
        <param name="notificationHubPath">通知ハブのパス。</param>
        <summary>接続文字列からクライアントを作成します。</summary>
        <returns>作成された <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateClientFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.NotificationHubClient CreateClientFromConnectionString (string connectionString, string notificationHubPath, bool enableTestSend);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.NotificationHubClient CreateClientFromConnectionString(string connectionString, string notificationHubPath, bool enableTestSend) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateClientFromConnectionString(System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateClientFromConnectionString (connectionString As String, notificationHubPath As String, enableTestSend As Boolean) As NotificationHubClient" />
      <MemberSignature Language="F#" Value="static member CreateClientFromConnectionString : string * string * bool -&gt; Microsoft.Azure.NotificationHubs.NotificationHubClient" Usage="Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateClientFromConnectionString (connectionString, notificationHubPath, enableTestSend)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="notificationHubPath" Type="System.String" />
        <Parameter Name="enableTestSend" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="connectionString">接続文字列。</param>
        <param name="notificationHubPath">通知ハブのパス。</param>
        <param name="enableTestSend">テスト送信; を有効にする場合は trueそれ以外の場合は false です。</param>
        <summary>接続文字列からクライアントを作成します。</summary>
        <returns>作成された <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateGcmNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt; CreateGcmNativeRegistrationAsync (string gcmRegistrationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt; CreateGcmNativeRegistrationAsync(string gcmRegistrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateGcmNativeRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateGcmNativeRegistrationAsync (gcmRegistrationId As String) As Task(Of GcmRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateGcmNativeRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt;" Usage="notificationHubClient.CreateGcmNativeRegistrationAsync gcmRegistrationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="gcmRegistrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="gcmRegistrationId">GCM 登録 id。</param>
        <summary>ネイティブの GCM 登録を非同期に作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateGcmNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt; CreateGcmNativeRegistrationAsync (string gcmRegistrationId, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt; CreateGcmNativeRegistrationAsync(string gcmRegistrationId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateGcmNativeRegistrationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateGcmNativeRegistrationAsync (gcmRegistrationId As String, tags As IEnumerable(Of String)) As Task(Of GcmRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateGcmNativeRegistrationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt;" Usage="notificationHubClient.CreateGcmNativeRegistrationAsync (gcmRegistrationId, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="gcmRegistrationId" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="gcmRegistrationId">GCM 登録 id。</param>
        <param name="tags">タグ。</param>
        <summary>ネイティブの GCM 登録を非同期に作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateGcmTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt; CreateGcmTemplateRegistrationAsync (string gcmRegistrationId, string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt; CreateGcmTemplateRegistrationAsync(string gcmRegistrationId, string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateGcmTemplateRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateGcmTemplateRegistrationAsync (gcmRegistrationId As String, jsonPayload As String) As Task(Of GcmTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateGcmTemplateRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateGcmTemplateRegistrationAsync (gcmRegistrationId, jsonPayload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="gcmRegistrationId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="gcmRegistrationId">GCM 登録 id。</param>
        <param name="jsonPayload">JSON ペイロード。</param>
        <summary>テンプレートの GCM 登録を非同期に作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateGcmTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt; CreateGcmTemplateRegistrationAsync (string gcmRegistrationId, string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt; CreateGcmTemplateRegistrationAsync(string gcmRegistrationId, string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateGcmTemplateRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateGcmTemplateRegistrationAsync (gcmRegistrationId As String, jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of GcmTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateGcmTemplateRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateGcmTemplateRegistrationAsync (gcmRegistrationId, jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="gcmRegistrationId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="gcmRegistrationId">GCM 登録 id。</param>
        <param name="jsonPayload">JSON ペイロード。</param>
        <param name="tags">タグ。</param>
        <summary>テンプレートの GCM 登録を非同期に作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMpnsNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt; CreateMpnsNativeRegistrationAsync (string channelUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt; CreateMpnsNativeRegistrationAsync(string channelUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateMpnsNativeRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMpnsNativeRegistrationAsync (channelUri As String) As Task(Of MpnsRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateMpnsNativeRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt;" Usage="notificationHubClient.CreateMpnsNativeRegistrationAsync channelUri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="channelUri">チャネル URI です。</param>
        <summary>ネイティブの MPNS 登録を非同期に作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMpnsNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt; CreateMpnsNativeRegistrationAsync (string channelUri, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt; CreateMpnsNativeRegistrationAsync(string channelUri, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateMpnsNativeRegistrationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMpnsNativeRegistrationAsync (channelUri As String, tags As IEnumerable(Of String)) As Task(Of MpnsRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateMpnsNativeRegistrationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt;" Usage="notificationHubClient.CreateMpnsNativeRegistrationAsync (channelUri, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="channelUri">チャネル URI です。</param>
        <param name="tags">タグ。</param>
        <summary>ネイティブの MPNS 登録を非同期に作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMpnsTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt; CreateMpnsTemplateRegistrationAsync (string channelUri, string xmlTemplate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt; CreateMpnsTemplateRegistrationAsync(string channelUri, string xmlTemplate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateMpnsTemplateRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMpnsTemplateRegistrationAsync (channelUri As String, xmlTemplate As String) As Task(Of MpnsTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateMpnsTemplateRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateMpnsTemplateRegistrationAsync (channelUri, xmlTemplate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="xmlTemplate" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="channelUri">チャネル URI です。</param>
        <param name="xmlTemplate">XML テンプレートです。</param>
        <summary>テンプレートの MPNS 登録を非同期に作成します。 作成時に追加のプロパティを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" />メソッドです。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMpnsTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt; CreateMpnsTemplateRegistrationAsync (string channelUri, string xmlTemplate, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt; CreateMpnsTemplateRegistrationAsync(string channelUri, string xmlTemplate, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateMpnsTemplateRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMpnsTemplateRegistrationAsync (channelUri As String, xmlTemplate As String, tags As IEnumerable(Of String)) As Task(Of MpnsTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateMpnsTemplateRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateMpnsTemplateRegistrationAsync (channelUri, xmlTemplate, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="xmlTemplate" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="channelUri">チャネル URI です。</param>
        <param name="xmlTemplate">XML テンプレートです。</param>
        <param name="tags">タグ。</param>
        <summary>テンプレートの MPNS 登録を非同期に作成します。 作成時に追加のプロパティを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" />メソッドです。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateInstallation">
      <MemberSignature Language="C#" Value="public void CreateOrUpdateInstallation (Microsoft.Azure.NotificationHubs.Installation installation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CreateOrUpdateInstallation(class Microsoft.Azure.NotificationHubs.Installation installation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateOrUpdateInstallation(Microsoft.Azure.NotificationHubs.Installation)" />
      <MemberSignature Language="F#" Value="member this.CreateOrUpdateInstallation : Microsoft.Azure.NotificationHubs.Installation -&gt; unit" Usage="notificationHubClient.CreateOrUpdateInstallation installation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installation" Type="Microsoft.Azure.NotificationHubs.Installation" />
      </Parameters>
      <Docs>
        <param name="installation">デバイスのインストールのオブジェクト。</param>
        <summary>
            作成するか、デバイスのインストールを更新します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateInstallationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateOrUpdateInstallationAsync (Microsoft.Azure.NotificationHubs.Installation installation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateOrUpdateInstallationAsync(class Microsoft.Azure.NotificationHubs.Installation installation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateOrUpdateInstallationAsync(Microsoft.Azure.NotificationHubs.Installation)" />
      <MemberSignature Language="F#" Value="member this.CreateOrUpdateInstallationAsync : Microsoft.Azure.NotificationHubs.Installation -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.CreateOrUpdateInstallationAsync installation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installation" Type="Microsoft.Azure.NotificationHubs.Installation" />
      </Parameters>
      <Docs>
        <param name="installation">デバイスのインストールのオブジェクト。</param>
        <summary>
            作成するか、デバイスのインストールを非同期的に更新します。
            </summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">インストールのオブジェクトが null の場合にスローされます。</exception>
        <exception cref="T:System.InvalidOperationException">InstallationId を指定する必要があります。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateRegistrationAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; CreateOrUpdateRegistrationAsync&lt;T&gt; (T registration) where T : Microsoft.Azure.NotificationHubs.RegistrationDescription;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!!T&gt; CreateOrUpdateRegistrationAsync&lt;(class Microsoft.Azure.NotificationHubs.RegistrationDescription) T&gt;(!!T registration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateOrUpdateRegistrationAsync``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateOrUpdateRegistrationAsync(Of T As RegistrationDescription) (registration As T) As Task(Of T)" />
      <MemberSignature Language="F#" Value="member this.CreateOrUpdateRegistrationAsync : 'T -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)&gt; (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)" Usage="notificationHubClient.CreateOrUpdateRegistrationAsync registration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <BaseTypeName>Microsoft.Azure.NotificationHubs.RegistrationDescription</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="registration" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">登録の型。</typeparam>
        <param name="registration">作成または更新する登録です。</param>
        <summary>非同期に作成またはクライアントの登録を更新します。</summary>
        <returns>非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">RegistrationId オブジェクトが null の場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateRegistrationAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; CreateRegistrationAsync&lt;T&gt; (T registration) where T : Microsoft.Azure.NotificationHubs.RegistrationDescription;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!!T&gt; CreateRegistrationAsync&lt;(class Microsoft.Azure.NotificationHubs.RegistrationDescription) T&gt;(!!T registration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRegistrationAsync(Of T As RegistrationDescription) (registration As T) As Task(Of T)" />
      <MemberSignature Language="F#" Value="member this.CreateRegistrationAsync : 'T -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)&gt; (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)" Usage="notificationHubClient.CreateRegistrationAsync registration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <BaseTypeName>Microsoft.Azure.NotificationHubs.RegistrationDescription</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="registration" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">登録の型。</typeparam>
        <param name="registration">作成する登録です。</param>
        <summary>非同期的に、登録を作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            RegistrationDescription で NotificationHubPath が正しくありません。
            RegistrationId が null または空にする必要がありますか
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateRegistrationIdAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; CreateRegistrationIdAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; CreateRegistrationIdAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationIdAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRegistrationIdAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.CreateRegistrationIdAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="notificationHubClient.CreateRegistrationIdAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>登録識別子を非同期に作成します。</summary>
        <returns>非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt; CreateWindowsNativeRegistrationAsync (string channelUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt; CreateWindowsNativeRegistrationAsync(string channelUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateWindowsNativeRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateWindowsNativeRegistrationAsync (channelUri As String) As Task(Of WindowsRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateWindowsNativeRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt;" Usage="notificationHubClient.CreateWindowsNativeRegistrationAsync channelUri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="channelUri">チャネル URI です。</param>
        <summary>Windows のネイティブ登録情報を非同期に作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt; CreateWindowsNativeRegistrationAsync (string channelUri, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt; CreateWindowsNativeRegistrationAsync(string channelUri, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateWindowsNativeRegistrationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateWindowsNativeRegistrationAsync (channelUri As String, tags As IEnumerable(Of String)) As Task(Of WindowsRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateWindowsNativeRegistrationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt;" Usage="notificationHubClient.CreateWindowsNativeRegistrationAsync (channelUri, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="channelUri">チャネル URI です。</param>
        <param name="tags">タグ。</param>
        <summary>Windows のネイティブ登録情報を非同期に作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt; CreateWindowsTemplateRegistrationAsync (string channelUri, string xmlTemplate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt; CreateWindowsTemplateRegistrationAsync(string channelUri, string xmlTemplate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateWindowsTemplateRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateWindowsTemplateRegistrationAsync (channelUri As String, xmlTemplate As String) As Task(Of WindowsTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateWindowsTemplateRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateWindowsTemplateRegistrationAsync (channelUri, xmlTemplate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="xmlTemplate" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="channelUri">チャネル URI です。</param>
        <param name="xmlTemplate">XML テンプレートです。</param>
        <summary>Windows テンプレート登録を非同期に作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt; CreateWindowsTemplateRegistrationAsync (string channelUri, string xmlTemplate, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt; CreateWindowsTemplateRegistrationAsync(string channelUri, string xmlTemplate, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateWindowsTemplateRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateWindowsTemplateRegistrationAsync (channelUri As String, xmlTemplate As String, tags As IEnumerable(Of String)) As Task(Of WindowsTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateWindowsTemplateRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateWindowsTemplateRegistrationAsync (channelUri, xmlTemplate, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="xmlTemplate" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="channelUri">チャネル URI です。</param>
        <param name="xmlTemplate">XML テンプレートです。</param>
        <param name="tags">タグ。</param>
        <summary>Windows テンプレート登録を非同期に作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteInstallation">
      <MemberSignature Language="C#" Value="public void DeleteInstallation (string installationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteInstallation(string installationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteInstallation(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteInstallation (installationId As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteInstallation : string -&gt; unit" Usage="notificationHubClient.DeleteInstallation installationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="installationId">インストールの識別子です。</param>
        <summary>
            インストールを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteInstallationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteInstallationAsync (string installationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteInstallationAsync(string installationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteInstallationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteInstallationAsync (installationId As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteInstallationAsync : string -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.DeleteInstallationAsync installationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="installationId">インストールの識別子です。</param>
        <summary>
            インストールを非同期的に削除します。
            </summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">InstallationId オブジェクトが null の場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRegistrationAsync (Microsoft.Azure.NotificationHubs.RegistrationDescription registration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRegistrationAsync(class Microsoft.Azure.NotificationHubs.RegistrationDescription registration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteRegistrationAsync(Microsoft.Azure.NotificationHubs.RegistrationDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRegistrationAsync (registration As RegistrationDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRegistrationAsync : Microsoft.Azure.NotificationHubs.RegistrationDescription -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.DeleteRegistrationAsync registration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="registration" Type="Microsoft.Azure.NotificationHubs.RegistrationDescription" />
      </Parameters>
      <Docs>
        <param name="registration">削除する登録です。</param>
        <summary>非同期的に、登録を削除します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">登録オブジェクトが null の場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRegistrationAsync (string registrationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRegistrationAsync(string registrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRegistrationAsync (registrationId As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRegistrationAsync : string -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.DeleteRegistrationAsync registrationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="registrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="registrationId">登録 id。</param>
        <summary>非同期的に、登録を削除します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRegistrationAsync (string registrationId, string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRegistrationAsync(string registrationId, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRegistrationAsync (registrationId As String, etag As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.DeleteRegistrationAsync (registrationId, etag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="registrationId" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="registrationId">登録 id。</param>
        <param name="etag">エンティティ タグ。</param>
        <summary>非同期的に、登録を削除します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">RegistrationId</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteRegistrationsByChannelAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRegistrationsByChannelAsync (string pnsHandle);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRegistrationsByChannelAsync(string pnsHandle) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteRegistrationsByChannelAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRegistrationsByChannelAsync (pnsHandle As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRegistrationsByChannelAsync : string -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.DeleteRegistrationsByChannelAsync pnsHandle" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pnsHandle" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pnsHandle">PNS が処理されます。</param>
        <summary>非同期的にチャネルでの登録を削除します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">pnsHandle</exception>
      </Docs>
    </Member>
    <Member MemberName="EnableTestSend">
      <MemberSignature Language="C#" Value="public bool EnableTestSend { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableTestSend" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubClient.EnableTestSend" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnableTestSend As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableTestSend : bool" Usage="Microsoft.Azure.NotificationHubs.NotificationHubClient.EnableTestSend" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはクライアントにテスト送信が有効かどうかを示す値を設定します。</summary>
        <value>クライアントでは、テストの場合は true を送信します。それ以外の場合は false です。</value>
        <remarks>
            テストの送信が有効になっているときに、以下の処理が行われます。
            <ul><li>すべての通知では、送信呼び出しごとに最大 10 個のデバイスにのみアクセスできます。</li><li><b>送信 *</b>メソッドには、これらすべての通知配信の結果の一覧が返されます。 返される結果は、製品利用統計情報に表示されることと同じです。 結果には、認証エラー、エラー、正常に配信したファイル、およびなどの調整などが含まれています。</li></ul><p>このモードは、実稼働環境ではなくテスト目的でのみが着信します。</p></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllRegistrationsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetAllRegistrationsAsync (int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetAllRegistrationsAsync(int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetAllRegistrationsAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllRegistrationsAsync (top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetAllRegistrationsAsync : int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetAllRegistrationsAsync top" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="top">登録の場所です。</param>
        <summary>この通知ハブのすべての登録を非同期に取得します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllRegistrationsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetAllRegistrationsAsync (string continuationToken, int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetAllRegistrationsAsync(string continuationToken, int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetAllRegistrationsAsync(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllRegistrationsAsync (continuationToken As String, top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetAllRegistrationsAsync : string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetAllRegistrationsAsync (continuationToken, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="continuationToken">継続トークンです。</param>
        <param name="top">登録の場所です。</param>
        <summary>この通知ハブのすべての登録を非同期に取得します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBaseUri">
      <MemberSignature Language="C#" Value="public Uri GetBaseUri ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Uri GetBaseUri() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetBaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBaseUri () As Uri" />
      <MemberSignature Language="F#" Value="member this.GetBaseUri : unit -&gt; Uri" Usage="notificationHubClient.GetBaseUri " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>BaseUri 添付プロパティの値を取得します。</summary>
        <returns>指定された要素のベース URI。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInstallation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Installation GetInstallation (string installationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.NotificationHubs.Installation GetInstallation(string installationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetInstallation(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetInstallation (installationId As String) As Installation" />
      <MemberSignature Language="F#" Value="member this.GetInstallation : string -&gt; Microsoft.Azure.NotificationHubs.Installation" Usage="notificationHubClient.GetInstallation installationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Installation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="installationId">インストールの識別子です。</param>
        <summary>
            デバイスのインストールのオブジェクトを取得します。
            </summary>
        <returns>デバイスのインストール オブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInstallationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.Installation&gt; GetInstallationAsync (string installationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.Installation&gt; GetInstallationAsync(string installationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetInstallationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetInstallationAsync (installationId As String) As Task(Of Installation)" />
      <MemberSignature Language="F#" Value="member this.GetInstallationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.Installation&gt;" Usage="notificationHubClient.GetInstallationAsync installationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.Installation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="installationId">インストールの識別子です。</param>
        <summary>
            インストールを非同期に取得します。
            </summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">InstallationId オブジェクトが null の場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; GetNotificationHubJobAsync (string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; GetNotificationHubJobAsync(string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetNotificationHubJobAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubJobAsync (jobId As String) As Task(Of NotificationHubJob)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubJobAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;" Usage="notificationHubClient.GetNotificationHubJobAsync jobId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId">使用して新しいジョブを作成した後、ジョブ Id が返される<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob)" />です。</param>
        <summary>
            JobId を指定したを返します、関連付けられている<see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />です。 このメソッドを使用して、そのジョブに完了し、失敗、または、処理中であるかどうかに表示するジョブの状態を取得します。
            この API は、標準の名前空間のできるだけです。
            </summary>
        <returns>
            現在の状態、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob)" />です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubJobsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt; GetNotificationHubJobsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt; GetNotificationHubJobsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetNotificationHubJobsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubJobsAsync () As Task(Of IEnumerable(Of NotificationHubJob))" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubJobsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt;" Usage="notificationHubClient.GetNotificationHubJobsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            返しますのすべての既知<see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s。 このメソッドを使用して、それらのジョブが完了、失敗したか、まだ進行中かどうかをすべてのジョブの状態を取得します。
            この API は、標準の名前空間のできるだけです。
            </summary>
        <returns>
            現在の状態、 <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationOutcomeDetailsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationDetails&gt; GetNotificationOutcomeDetailsAsync (string notificationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationDetails&gt; GetNotificationOutcomeDetailsAsync(string notificationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetNotificationOutcomeDetailsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationOutcomeDetailsAsync (notificationId As String) As Task(Of NotificationDetails)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationOutcomeDetailsAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationDetails&gt;" Usage="notificationHubClient.GetNotificationOutcomeDetailsAsync notificationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationDetails&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notificationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="notificationId">
          <see cref="P:Microsoft.Azure.NotificationHubs.NotificationOutcome.NotificationId" />これには、送信 * を呼び出すときに返されました。</param>
        <summary>
            送信 * 操作の結果を取得します。 送信 * が完了した場合これで、送信が処理されている場合、結果を中間または最終結果を取得できます。 この API は、標準の名前空間に対してのみ呼び出すことができます。
            </summary>
        <returns>
            によって表される、送信操作の結果、<see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />です。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">notificationId</exception>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationAsync&lt;TRegistrationDescription&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TRegistrationDescription&gt; GetRegistrationAsync&lt;TRegistrationDescription&gt; (string registrationId) where TRegistrationDescription : Microsoft.Azure.NotificationHubs.RegistrationDescription;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!!TRegistrationDescription&gt; GetRegistrationAsync&lt;(class Microsoft.Azure.NotificationHubs.RegistrationDescription) TRegistrationDescription&gt;(string registrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetRegistrationAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRegistrationAsync(Of TRegistrationDescription As RegistrationDescription) (registrationId As String) As Task(Of TRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;'RegistrationDescription (requires 'RegistrationDescription :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)&gt; (requires 'RegistrationDescription :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)" Usage="notificationHubClient.GetRegistrationAsync registrationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TRegistrationDescription">
          <Constraints>
            <BaseTypeName>Microsoft.Azure.NotificationHubs.RegistrationDescription</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="registrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TRegistrationDescription">登録の説明の種類。</typeparam>
        <param name="registrationId">登録 id。</param>
        <summary>指定された ID の登録を非同期的に取得します。 登録の種類によって異なります、指定した<paramref name="TRegistrationDescription" />パラメーター。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">RegistrationId が null の場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationsByChannelAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByChannelAsync (string pnsHandle, int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByChannelAsync(string pnsHandle, int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetRegistrationsByChannelAsync(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRegistrationsByChannelAsync (pnsHandle As String, top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRegistrationsByChannelAsync : string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetRegistrationsByChannelAsync (pnsHandle, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pnsHandle" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="pnsHandle">PNS が処理されます。</param>
        <param name="top">登録の場所です。</param>
        <summary>チャネルによって、登録を非同期に取得します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationsByChannelAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByChannelAsync (string pnsHandle, string continuationToken, int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByChannelAsync(string pnsHandle, string continuationToken, int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetRegistrationsByChannelAsync(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRegistrationsByChannelAsync (pnsHandle As String, continuationToken As String, top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRegistrationsByChannelAsync : string * string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetRegistrationsByChannelAsync (pnsHandle, continuationToken, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pnsHandle" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="pnsHandle">PNS が処理されます。</param>
        <param name="continuationToken">継続トークンです。</param>
        <param name="top">登録の場所です。</param>
        <summary>チャネルによって、登録を非同期に取得します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">pnsHandle</exception>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationsByTagAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByTagAsync (string tag, int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByTagAsync(string tag, int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetRegistrationsByTagAsync(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRegistrationsByTagAsync (tag As String, top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRegistrationsByTagAsync : string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetRegistrationsByTagAsync (tag, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tag" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="tag">タグ。</param>
        <param name="top">場所の登録を取得する場所です。</param>
        <summary>タグで、登録を非同期に取得します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationsByTagAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByTagAsync (string tag, string continuationToken, int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByTagAsync(string tag, string continuationToken, int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetRegistrationsByTagAsync(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRegistrationsByTagAsync (tag As String, continuationToken As String, top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRegistrationsByTagAsync : string * string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetRegistrationsByTagAsync (tag, continuationToken, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tag" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="tag">タグ。</param>
        <param name="continuationToken">継続トークンです。</param>
        <param name="top">場所の登録を取得する場所です。</param>
        <summary>タグで、登録を非同期に取得します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">タグのオブジェクトが null の場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="PatchInstallation">
      <MemberSignature Language="C#" Value="public void PatchInstallation (string installationId, System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; operations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void PatchInstallation(string installationId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.PatchInstallation(System.String,System.Collections.Generic.IList{Microsoft.Azure.NotificationHubs.PartialUpdateOperation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub PatchInstallation (installationId As String, operations As IList(Of PartialUpdateOperation))" />
      <MemberSignature Language="F#" Value="member this.PatchInstallation : string * System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; -&gt; unit" Usage="notificationHubClient.PatchInstallation (installationId, operations)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
        <Parameter Name="operations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt;" />
      </Parameters>
      <Docs>
        <param name="installationId">インストールの識別子です。</param>
        <param name="operations">更新操作のコレクション。</param>
        <summary>
            修正プログラムのインストール。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchInstallationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PatchInstallationAsync (string installationId, System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; operations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PatchInstallationAsync(string installationId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.PatchInstallationAsync(System.String,System.Collections.Generic.IList{Microsoft.Azure.NotificationHubs.PartialUpdateOperation})" />
      <MemberSignature Language="VB.NET" Value="Public Function PatchInstallationAsync (installationId As String, operations As IList(Of PartialUpdateOperation)) As Task" />
      <MemberSignature Language="F#" Value="member this.PatchInstallationAsync : string * System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.PatchInstallationAsync (installationId, operations)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
        <Parameter Name="operations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt;" />
      </Parameters>
      <Docs>
        <param name="installationId">インストールの識別子です。</param>
        <param name="operations">更新操作のコレクション。</param>
        <summary>
            インストールを修正プログラムには、次の非同期的にします。
            </summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            InstallationId または操作のオブジェクトが null の場合にスローされます。
            </exception>
        <exception cref="T:System.InvalidOperationException">操作リストが空の場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="RegistrationExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; RegistrationExistsAsync (string registrationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; RegistrationExistsAsync(string registrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.RegistrationExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegistrationExistsAsync (registrationId As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RegistrationExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="notificationHubClient.RegistrationExistsAsync registrationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="registrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="registrationId">登録 id。</param>
        <summary>非同期的に、登録が既に存在することを示します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, DateTimeOffset scheduledTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, valuetype System.DateTimeOffset scheduledTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.ScheduleNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.ScheduleNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;" Usage="notificationHubClient.ScheduleNotificationAsync (notification, scheduledTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="scheduledTime" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="notification">通知です。</param>
        <param name="scheduledTime">スケジュールされた時刻。</param>
        <summary>
            通知を非同期的にスケジュールします。
            </summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, DateTimeOffset scheduledTime, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, valuetype System.DateTimeOffset scheduledTime, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.ScheduleNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.DateTimeOffset,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="F#" Value="member this.ScheduleNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * DateTimeOffset * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;" Usage="notificationHubClient.ScheduleNotificationAsync (notification, scheduledTime, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="scheduledTime" Type="System.DateTimeOffset" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="notification">通知です。</param>
        <param name="scheduledTime">スケジュールされた時刻。</param>
        <param name="tags">タグ。</param>
        <summary>
            通知を非同期的にスケジュールします。
            </summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">タグのオブジェクトが null の場合にスローされます。</exception>
        <exception cref="T:System.ArgumentException">タグの引数は、少なくとも 1 つのタグを含める必要があります。</exception>
      </Docs>
    </Member>
    <Member MemberName="ScheduleNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, DateTimeOffset scheduledTime, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, valuetype System.DateTimeOffset scheduledTime, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.ScheduleNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.DateTimeOffset,System.String)" />
      <MemberSignature Language="F#" Value="member this.ScheduleNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * DateTimeOffset * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;" Usage="notificationHubClient.ScheduleNotificationAsync (notification, scheduledTime, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="scheduledTime" Type="System.DateTimeOffset" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="notification">通知です。</param>
        <param name="scheduledTime">スケジュールされた時刻。</param>
        <param name="tagExpression">タグ式です。</param>
        <summary>
            通知を非同期的にスケジュールします。
            </summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAdmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync (string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync(string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAdmNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAdmNativeNotificationAsync (jsonPayload As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAdmNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAdmNativeNotificationAsync jsonPayload" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload">JSON ペイロード。</param>
        <summary>管理用のネイティブ通知を非同期的に送信します。</summary>
        <returns>非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAdmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync (string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync(string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAdmNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAdmNativeNotificationAsync (jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAdmNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAdmNativeNotificationAsync (jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="jsonPayload">JSON ペイロード。</param>
        <param name="tags">タグ。</param>
        <summary>管理用のネイティブ通知を非同期的に送信します。</summary>
        <returns>非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAdmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync (string jsonPayload, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync(string jsonPayload, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAdmNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAdmNativeNotificationAsync (jsonPayload As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAdmNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAdmNativeNotificationAsync (jsonPayload, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload">JSON ペイロード。</param>
        <param name="tagExpression">タグ式です。</param>
        <summary>管理用のネイティブ通知を非同期的に送信します。</summary>
        <returns>非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAppleNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync (string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync(string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAppleNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAppleNativeNotificationAsync (jsonPayload As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAppleNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAppleNativeNotificationAsync jsonPayload" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload">JSON ペイロード。</param>
        <summary>Apple ネイティブ通知を非同期的に送信します。 有効期限を指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAppleNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync (string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync(string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAppleNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAppleNativeNotificationAsync (jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAppleNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAppleNativeNotificationAsync (jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="jsonPayload">JSON ペイロード。</param>
        <param name="tags">以外の空のセット タグ (最大 20 タグ)。 セット内の各文字列は、1 つのタグを含めることができます。</param>
        <summary>非同期的にネイティブ通知を Apple に非-空タグのセット (最大 20) を送信します。 これは、ブール型 Or でタグが付けられた式と同じ ("| |") です。 有効期限を指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAppleNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync (string jsonPayload, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync(string jsonPayload, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAppleNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAppleNativeNotificationAsync (jsonPayload As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAppleNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAppleNativeNotificationAsync (jsonPayload, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload">JSON ペイロード。</param>
        <param name="tagExpression">タグ式は、論理演算子を使用して構築された任意のブール式 AND (&amp;&amp;)、または (|)、されません (!)、かっこを丸めるとします。 例: (A | |B) &amp; &amp; !C. 式には、Or のみが使用されている場合は、最大で 20 タグが含まれてことができます。 その他の式は、6 つのタグに制限されます。 1 つのタグ"A"が有効な式であることを注意してください。</param>
        <summary>非同期的に (1 つのタグ「タグ」は有効なタグ式) タグ式に Apple ネイティブ通知を送信します。 有効期限を指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBaiduNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendBaiduNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBaiduNativeNotificationAsync (message As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendBaiduNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendBaiduNativeNotificationAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">これは、json 要求です。 Baidu、json 形式のドキュメント<a href="http://push.baidu.com/doc/restapi/restapi">ここ</a>です。</param>
        <summary>
            Baidu ネイティブ通知を送信します。
            </summary>
        <returns>
          <see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />これには、送信操作の結果について説明します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBaiduNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync (string message, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync(string message, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendBaiduNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBaiduNativeNotificationAsync (message As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendBaiduNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendBaiduNativeNotificationAsync (message, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="message">これは、json 要求です。 Baidu、json 形式のドキュメント<a href="http://push.baidu.com/doc/restapi/restapi">ここ</a>です。</param>
        <param name="tags">以外の空のセット タグ (最大 20 タグ)。 セット内の各文字列は、1 つのタグを含めることができます。</param>
        <summary>
            (1 つのタグ「タグ」は有効なタグ式) タグ式には、Baidu ネイティブ通知を送信します。
            </summary>
        <returns>
          <see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />これには、送信操作の結果について説明します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBaiduNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync (string message, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync(string message, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendBaiduNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBaiduNativeNotificationAsync (message As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendBaiduNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendBaiduNativeNotificationAsync (message, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">これは、json 要求です。 Baidu、json 形式のドキュメント<a href="http://push.baidu.com/doc/restapi/restapi">ここ</a>です。</param>
        <param name="tagExpression">タグ式は、論理演算子を使用して構築された任意のブール式 AND (&amp;&amp;)、または (|)、されません (!)、かっこを丸めるとします。 例: (A | |B) &amp; &amp; !C. 式には、Or のみが使用されている場合は、最大で 20 タグが含まれてことができます。 その他の式は、6 つのタグに制限されます。 1 つのタグ"A"が有効な式であることを注意してください。</param>
        <summary>
            (1 つのタグ「タグ」は有効なタグ式) タグ式には、Baidu ネイティブ通知を送信します。
            </summary>
        <returns>
          <see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />これには、送信操作の結果について説明します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendGcmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync (string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync(string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendGcmNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendGcmNativeNotificationAsync (jsonPayload As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendGcmNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendGcmNativeNotificationAsync jsonPayload" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload">JSON ペイロード。</param>
        <summary>GCM ネイティブ通知を非同期的に送信します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendGcmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync (string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync(string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendGcmNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendGcmNativeNotificationAsync (jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendGcmNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendGcmNativeNotificationAsync (jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="jsonPayload">JSON ペイロード。</param>
        <param name="tags">以外の空のセット タグ (最大 20 タグ)。 セット内の各文字列は、1 つのタグを含めることができます。</param>
        <summary>非同期的に GCM ネイティブ通知を非-空タグのセット (最大 20) を送信します。 これは、ブール型 Or とタグ式と同じ ("| |") です。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendGcmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync (string jsonPayload, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync(string jsonPayload, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendGcmNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendGcmNativeNotificationAsync (jsonPayload As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendGcmNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendGcmNativeNotificationAsync (jsonPayload, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload">JSON ペイロード。</param>
        <param name="tagExpression">タグ式は、論理演算子を使用して構築された任意のブール式 AND (&amp;&amp;)、または (|)、されません (!)、かっこを丸めるとします。 例: (A | |B) &amp; &amp; !C. 式には、Or のみが使用されている場合は、最大で 20 タグが含まれてことができます。 その他の式は、6 つのタグに制限されます。 1 つのタグ"A"が有効な式であることを注意してください。</param>
        <summary>非同期的に (1 つのタグ「タグ」は有効なタグ式) タグ式に GCM ネイティブ通知を送信します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendMpnsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync (string nativePayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync(string nativePayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendMpnsNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendMpnsNativeNotificationAsync (nativePayload As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendMpnsNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendMpnsNativeNotificationAsync nativePayload" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nativePayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nativePayload">ネイティブのペイロード。</param>
        <summary>MPNS ネイティブ通知を非同期的に送信します。 MPNS のヘッダーを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendMpnsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync (string nativePayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync(string nativePayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendMpnsNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendMpnsNativeNotificationAsync (nativePayload As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendMpnsNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendMpnsNativeNotificationAsync (nativePayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nativePayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="nativePayload">通知のペイロード。</param>
        <param name="tags">以外の空のセット タグ (最大 20 タグ)。 セット内の各文字列は、1 つのタグを含めることができます。</param>
        <summary>非同期 MPNS ネイティブ通知を非-空タグのセット (最大 20) を送信します。 これは、ブール型 Or とタグ式と同じ ("| |") です。 MPNS のヘッダーを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendMpnsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync (string nativePayload, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync(string nativePayload, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendMpnsNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendMpnsNativeNotificationAsync (nativePayload As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendMpnsNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendMpnsNativeNotificationAsync (nativePayload, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nativePayload" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nativePayload">ネイティブのペイロード。</param>
        <param name="tagExpression">タグ式は、論理演算子を使用して構築された任意のブール式 AND (&amp;&amp;)、または (|)、されません (!)、かっこを丸めるとします。 例: (A | |B) &amp; &amp; !C. 式には、Or のみが使用されている場合は、最大で 20 タグが含まれてことができます。 その他の式は、6 つのタグに制限されます。 1 つのタグ"A"が有効な式であることを注意してください。</param>
        <summary>非同期的に (1 つのタグ「タグ」は有効なタグ式) タグ式に MPNS ネイティブ通知を送信します。 MPNS のヘッダーを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />
      <MemberSignature Language="F#" Value="member this.SendNotificationAsync : Microsoft.Azure.NotificationHubs.Notification -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendNotificationAsync notification" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
      </Parameters>
      <Docs>
        <param name="notification">送信する通知。</param>
        <summary>非同期通知を非-空タグのセット (最大 20) を送信します。 これは、ブール型 Or とタグ式と同じ ("| |") です。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">通知</exception>
      </Docs>
    </Member>
    <Member MemberName="SendNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="F#" Value="member this.SendNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendNotificationAsync (notification, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="notification">送信する通知。</param>
        <param name="tags">以外の空のセット タグ (最大 20 タグ)。 セット内の各文字列は、1 つのタグを含めることができます。</param>
        <summary>非同期通知を非-空タグのセット (最大 20) を送信します。 これは、ブール型 Or とタグ式と同じ ("| |") です。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            通知またはタグのオブジェクトが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentException">
            通知します。Tag プロパティを null することはできませんまたはタグの引数は atleat 1 つのタグを含める必要があります。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SendNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.String)" />
      <MemberSignature Language="F#" Value="member this.SendNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendNotificationAsync (notification, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="notification">送信する通知。</param>
        <param name="tagExpression">タグ式は、論理演算子を使用して構築された任意のブール式 AND (&amp;&amp;)、または (|)、されません (!)、かっこを丸めるとします。 例: (A | |B) &amp; &amp; !C. 式には、Or のみが使用されている場合は、最大で 20 タグが含まれてことができます。 その他の式は、6 つのタグに制限されます。 1 つのタグ"A"が有効な式であることを注意してください。</param>
        <summary>非同期的に (1 つのタグ「タグ」は有効なタグ式) タグ式に通知を送信します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">通知</exception>
        <exception cref="T:System.ArgumentException">通知します。Tag プロパティを null にする必要があります。</exception>
      </Docs>
    </Member>
    <Member MemberName="SendTemplateNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendTemplateNotificationAsync(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendTemplateNotificationAsync (properties As IDictionary(Of String, String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendTemplateNotificationAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendTemplateNotificationAsync properties" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="properties">テンプレートのプロパティです。</param>
        <summary>テンプレート通知を非同期的に送信します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendTemplateNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; properties, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendTemplateNotificationAsync(System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendTemplateNotificationAsync (properties As IDictionary(Of String, String), tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendTemplateNotificationAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendTemplateNotificationAsync (properties, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="properties">テンプレートのプロパティです。</param>
        <param name="tags">以外の空のセット タグ (最大 20 タグ)。 セット内の各文字列は、1 つのタグを含めることができます。</param>
        <summary>非同期に非-空タグのセット (最大 20) のテンプレート通知を送信します。 これは、ブール型 Or とタグ式と同じ ("| |") です。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendTemplateNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; properties, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendTemplateNotificationAsync(System.Collections.Generic.IDictionary{System.String,System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendTemplateNotificationAsync (properties As IDictionary(Of String, String), tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendTemplateNotificationAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendTemplateNotificationAsync (properties, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="properties">テンプレートのプロパティです。</param>
        <param name="tagExpression">タグ式は、論理演算子を使用して構築された任意のブール式 AND (&amp;&amp;)、または (|)、されません (!)、かっこを丸めるとします。 例: (A | |B) &amp; &amp; !C. 式には、Or のみが使用されている場合は、最大で 20 タグが含まれてことができます。 その他の式は、6 つのタグに制限されます。 1 つのタグ"A"が有効な式であることを注意してください。</param>
        <summary>非同期的に (1 つのタグ「タグ」は有効なタグ式) タグ式に、テンプレート通知を送信します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendWindowsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync (string windowsNativePayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync(string windowsNativePayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendWindowsNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendWindowsNativeNotificationAsync (windowsNativePayload As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendWindowsNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendWindowsNativeNotificationAsync windowsNativePayload" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="windowsNativePayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="windowsNativePayload">Windows ネイティブ ペイロード。</param>
        <summary>Windows のネイティブ通知を非同期的に送信します。 WNS のヘッダーを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendWindowsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync (string windowsNativePayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync(string windowsNativePayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendWindowsNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendWindowsNativeNotificationAsync (windowsNativePayload As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendWindowsNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendWindowsNativeNotificationAsync (windowsNativePayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="windowsNativePayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="windowsNativePayload">Windows ネイティブ ペイロード。</param>
        <param name="tags">以外の空のセット タグ (最大 20 タグ)。 セット内の各文字列は、1 つのタグを含めることができます。</param>
        <summary>非同期に非-空タグのセット (最大 20) の Windows ネイティブ通知を送信します。 これは、ブール型 Or とタグ式と同じ ("| |") です。 WNS のヘッダーを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendWindowsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync (string windowsNativePayload, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync(string windowsNativePayload, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendWindowsNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendWindowsNativeNotificationAsync (windowsNativePayload As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendWindowsNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendWindowsNativeNotificationAsync (windowsNativePayload, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="windowsNativePayload" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="windowsNativePayload">Windows ネイティブ ペイロード。</param>
        <param name="tagExpression">タグ式は、論理演算子を使用して構築された任意のブール式 AND (&amp;&amp;)、または (|)、されません (!)、かっこを丸めるとします。 例: (A | |B) &amp; &amp; !C. 式には、Or のみが使用されている場合は、最大で 20 タグが含まれてことができます。 その他の式は、6 つのタグに制限されます。 1 つのタグ"A"が有効な式であることを注意してください。</param>
        <summary>(1 つのタグ「タグ」は有効なタグ式) タグ式に、Windows ネイティブ通知を非同期的に送信します。 WNS のヘッダーを指定するには、使用、<see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />メソッドです。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitNotificationHubJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; SubmitNotificationHubJobAsync (Microsoft.Azure.NotificationHubs.NotificationHubJob job);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; SubmitNotificationHubJobAsync(class Microsoft.Azure.NotificationHubs.NotificationHubJob job) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubmitNotificationHubJobAsync (job As NotificationHubJob) As Task(Of NotificationHubJob)" />
      <MemberSignature Language="F#" Value="member this.SubmitNotificationHubJobAsync : Microsoft.Azure.NotificationHubs.NotificationHubJob -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;" Usage="notificationHubClient.SubmitNotificationHubJobAsync job" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.NotificationHubs.NotificationHubJob" />
      </Parameters>
      <Docs>
        <param name="job"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />登録をエクスポートするには、登録をインポートまたは登録を作成します。</param>
        <summary>
            <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" /> を作成します。 この API は、標準の名前空間のできるだけです。
            </summary>
        <returns>
            送信済み<see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRegistrationAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; UpdateRegistrationAsync&lt;T&gt; (T registration) where T : Microsoft.Azure.NotificationHubs.RegistrationDescription;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!!T&gt; UpdateRegistrationAsync&lt;(class Microsoft.Azure.NotificationHubs.RegistrationDescription) T&gt;(!!T registration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.UpdateRegistrationAsync``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRegistrationAsync(Of T As RegistrationDescription) (registration As T) As Task(Of T)" />
      <MemberSignature Language="F#" Value="member this.UpdateRegistrationAsync : 'T -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)&gt; (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)" Usage="notificationHubClient.UpdateRegistrationAsync registration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <BaseTypeName>Microsoft.Azure.NotificationHubs.RegistrationDescription</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="registration" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">登録の型。</typeparam>
        <param name="registration">更新する登録です。</param>
        <summary>非同期的に、登録を更新します。</summary>
        <returns>更新プログラムが終了するときに完了するタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            RegistrationId または ETag オブジェクトが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>
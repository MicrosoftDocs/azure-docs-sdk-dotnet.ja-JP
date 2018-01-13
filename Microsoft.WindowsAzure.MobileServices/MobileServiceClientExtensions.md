<Type Name="MobileServiceClientExtensions" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceClientExtensions">
  <TypeSignature Language="C#" Value="public static class MobileServiceClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MobileServiceClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MobileServiceClientExtensions" />
  <TypeSignature Language="F#" Value="type MobileServiceClientExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             拡張メソッドを提供<see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServiceClient" />です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="LoginWithMicrosoftAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; LoginWithMicrosoftAccountAsync (this Microsoft.WindowsAzure.MobileServices.MobileServiceClient thisClient, string authenticationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; LoginWithMicrosoftAccountAsync(class Microsoft.WindowsAzure.MobileServices.MobileServiceClient thisClient, string authenticationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClientExtensions.LoginWithMicrosoftAccountAsync(Microsoft.WindowsAzure.MobileServices.MobileServiceClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function LoginWithMicrosoftAccountAsync (thisClient As MobileServiceClient, authenticationToken As String) As Task(Of MobileServiceUser)" />
      <MemberSignature Language="F#" Value="static member LoginWithMicrosoftAccountAsync : Microsoft.WindowsAzure.MobileServices.MobileServiceClient * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClientExtensions.LoginWithMicrosoftAccountAsync (thisClient, authenticationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thisClient" Type="Microsoft.WindowsAzure.MobileServices.MobileServiceClient" RefType="this" />
        <Parameter Name="authenticationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="thisClient">
            ログインに使用するクライアント。
            </param>
        <param name="authenticationToken">
            Live SDK セッションの認証トークンです。
            </param>
        <summary>
            指定した Microsoft アカウントの認証トークンがモバイル サービス アプリケーションにユーザーをログインします。
            </summary>
        <returns>
            ユーザーが認証を終了するとタスクが完了します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
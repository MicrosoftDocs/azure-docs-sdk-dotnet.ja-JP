<Type Name="PromptBehavior" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior">
  <TypeSignature Language="C#" Value="public enum PromptBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed PromptBehavior extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior" />
  <TypeSignature Language="VB.NET" Value="Public Enum PromptBehavior" />
  <TypeSignature Language="F#" Value="type PromptBehavior = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            かどうか AcquireToken は自動的に入力を求めるために必要な場合にのみもかどうかに関係なく促す必要があるかどうかを示すキャッシュされたトークンがあります。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Always">
      <MemberSignature Language="C#" Value="Always" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior Always = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Always" />
      <MemberSignature Language="VB.NET" Value="Always" />
      <MemberSignature Language="F#" Value="Always = 1" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Always" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            既にキャッシュ内の要件を満たすトークンがある場合でも、ユーザーが資格情報を求められます。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Auto">
      <MemberSignature Language="C#" Value="Auto" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior Auto = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Auto" />
      <MemberSignature Language="VB.NET" Value="Auto" />
      <MemberSignature Language="F#" Value="Auto = 0" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Auto" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            取得トークンは、ユーザーに必要な場合にのみの資格情報を求められます。  要件を満たすトークンが既にキャッシュされている場合、ユーザーは求められません。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Never">
      <MemberSignature Language="C#" Value="Never" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior Never = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Never" />
      <MemberSignature Language="VB.NET" Value="Never" />
      <MemberSignature Language="F#" Value="Never = 2" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Never" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            ユーザーはいない資格情報を求められます。  メッセージを表示することが必要な場合は、AcquireToken 要求は失敗します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RefreshSession">
      <MemberSignature Language="C#" Value="RefreshSession" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior RefreshSession = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.RefreshSession" />
      <MemberSignature Language="VB.NET" Value="RefreshSession" />
      <MemberSignature Language="F#" Value="RefreshSession = 3" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.RefreshSession" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            再 (webview を表示する) を通じて許可、リソースの利用状況、結果のアクセス トークンが更新されたクレームが含まれていることを確認します。 ユーザー ログオンの cookie が使用可能な場合は、ユーザーが求められることがなく資格情報をもう一度とログオン ダイアログ ボックスが自動的に閉じます。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="SelectAccount">
      <MemberSignature Language="C#" Value="SelectAccount" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior SelectAccount = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.SelectAccount" />
      <MemberSignature Language="VB.NET" Value="SelectAccount" />
      <MemberSignature Language="F#" Value="SelectAccount = 4" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.SelectAccount" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            既にキャッシュ内の要件を満たすトークンがある場合でも、ユーザー アカウントを選択するように求めます。 これにより、承認サーバーの現在のセッションがある場合、複数のアカウント間で選択するのに複数のアカウントを持っているユーザーです。 
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>
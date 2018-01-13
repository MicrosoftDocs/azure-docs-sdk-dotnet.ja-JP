<Type Name="IPushUtility" FullName="Microsoft.WindowsAzure.MobileServices.IPushUtility">
  <TypeSignature Language="C#" Value="public interface IPushUtility" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPushUtility" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.IPushUtility" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPushUtility" />
  <TypeSignature Language="F#" Value="type IPushUtility = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            プッシュ機能に関するユーティリティ関数を提供するプラットフォーム固有のアセンブリのインターフェイスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetPlatform">
      <MemberSignature Language="C#" Value="public string GetPlatform ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetPlatform() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IPushUtility.GetPlatform" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPlatform () As String" />
      <MemberSignature Language="F#" Value="abstract member GetPlatform : unit -&gt; string" Usage="iPushUtility.GetPlatform " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            通知のプラットフォームを記述する文字列を返します
            </summary>
        <returns>
            通知のプラットフォームを記述する文字列。 例: gcm、apns、wns
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
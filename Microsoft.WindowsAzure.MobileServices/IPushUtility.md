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
            <span data-ttu-id="e83af-101">プッシュ機能に関するユーティリティ関数を提供するプラットフォーム固有のアセンブリのインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="e83af-101">An interface for platform-specific assemblies to provide utility functions regarding Push capabilities.</span></span>
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
            <span data-ttu-id="e83af-102">通知のプラットフォームを記述する文字列を返します</span><span class="sxs-lookup"><span data-stu-id="e83af-102">Return the string describing the notification platform</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e83af-103">通知のプラットフォームを記述する文字列。</span><span class="sxs-lookup"><span data-stu-id="e83af-103">String describing notfication platform.</span></span> <span data-ttu-id="e83af-104">例: gcm、apns、wns</span><span class="sxs-lookup"><span data-stu-id="e83af-104">Examples: gcm, apns, wns</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
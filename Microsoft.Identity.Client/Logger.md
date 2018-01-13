<Type Name="Logger" FullName="Microsoft.Identity.Client.Logger">
  <TypeSignature Language="C#" Value="public sealed class Logger" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Logger extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.Logger" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Logger" />
  <TypeSignature Language="F#" Value="type Logger = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1cbe4-101">により、開発者は、ログ レベルを構成する MSAL ロガー クラスは、コールバックなどを構成します。</span><span class="sxs-lookup"><span data-stu-id="1cbe4-101">MSAL Logger class that allows developers to configure log level, configure callbacks etc.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public static Microsoft.Identity.Client.Logger.LogLevel Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property valuetype Microsoft.Identity.Client.Logger/LogLevel Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.Logger.Level" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property Level As Logger.LogLevel" />
      <MemberSignature Language="F#" Value="member this.Level : Microsoft.Identity.Client.Logger.LogLevel with get, set" Usage="Microsoft.Identity.Client.Logger.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Identity.Client.Logger+LogLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cbe4-102">構成可能なログ レベルです。</span><span class="sxs-lookup"><span data-stu-id="1cbe4-102">Configurable log level.</span></span> <span data-ttu-id="1cbe4-103">既定値は、情報です。</span><span class="sxs-lookup"><span data-stu-id="1cbe4-103">Default value is Info.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogCallback">
      <MemberSignature Language="C#" Value="public static Microsoft.Identity.Client.LogCallback LogCallback { set; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Identity.Client.LogCallback LogCallback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.Logger.LogCallback" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property LogCallback As LogCallback" />
      <MemberSignature Language="F#" Value="member this.LogCallback : Microsoft.Identity.Client.LogCallback" Usage="Microsoft.Identity.Client.Logger.LogCallback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Identity.Client.LogCallback</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cbe4-104">消費し、カスタマイズされた方法でログを発行する開発者によって提供されるコールバック インスタンス。</span><span class="sxs-lookup"><span data-stu-id="1cbe4-104">Callback instance that can be provided by the developer to consume and publish logs in a custom manner.</span></span> <span data-ttu-id="1cbe4-105">プロパティは、1 回のみ設定でき、2 回呼び出された場合、ArgumentException をスローします。</span><span class="sxs-lookup"><span data-stu-id="1cbe4-105">The property can only be set once and it will throw an ArgumentException if called twice.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PiiLoggingEnabled">
      <MemberSignature Language="C#" Value="public static bool PiiLoggingEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property bool PiiLoggingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.Logger.PiiLoggingEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property PiiLoggingEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.PiiLoggingEnabled : bool with get, set" Usage="Microsoft.Identity.Client.Logger.PiiLoggingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cbe4-106">PII データのログ記録を有効または無効にするフラグです。</span><span class="sxs-lookup"><span data-stu-id="1cbe4-106">Flag to enable/disable logging of PII data.</span></span> <span data-ttu-id="1cbe4-107">コンソール、Logcat NSLog などの既定の出力には、PII のログは記録されません。</span><span class="sxs-lookup"><span data-stu-id="1cbe4-107">PII logs are never written to default outputs like Console, Logcat or NSLog.</span></span>
            <span data-ttu-id="1cbe4-108">既定値は false に設定します。</span><span class="sxs-lookup"><span data-stu-id="1cbe4-108">Default is set to false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
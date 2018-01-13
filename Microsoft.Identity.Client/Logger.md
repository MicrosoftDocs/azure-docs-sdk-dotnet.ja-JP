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
            により、開発者は、ログ レベルを構成する MSAL ロガー クラスは、コールバックなどを構成します。
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
            構成可能なログ レベルです。 既定値は、情報です。
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
            消費し、カスタマイズされた方法でログを発行する開発者によって提供されるコールバック インスタンス。 プロパティは、1 回のみ設定でき、2 回呼び出された場合、ArgumentException をスローします。
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
            PII データのログ記録を有効または無効にするフラグです。 コンソール、Logcat NSLog などの既定の出力には、PII のログは記録されません。
            既定値は false に設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="IWithData&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithData&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithData&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithData`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithData`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithData(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithData&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">アタッチした後に戻るに親アプリケーション ゲートウェイの段階です。</typeparam>
    <summary>
            SSL 証明書の内容を指定できるように、SSL 証明書の定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPfxFromBytes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword&lt;ParentT&gt; WithPfxFromBytes (params byte[] pfxData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword`1&lt;!ParentT&gt; WithPfxFromBytes(unsigned int8[] pfxData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithData`1.WithPfxFromBytes(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPfxFromBytes (ParamArray pfxData As Byte()) As IWithPassword(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPfxFromBytes : byte[] -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword&lt;'ParentT&gt;" Usage="iWithData.WithPfxFromBytes pfxData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxData" Type="System.Byte[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="pfxData">PFX 形式で秘密キーの内容。</param>
        <summary>
            Base64 でエンコードされたされません、PFX (PKCS #12) 形式で秘密キーの内容を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPfxFromFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword&lt;ParentT&gt; WithPfxFromFile (System.IO.FileInfo pfxFile);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword`1&lt;!ParentT&gt; WithPfxFromFile(class System.IO.FileInfo pfxFile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithData`1.WithPfxFromFile(System.IO.FileInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPfxFromFile (pfxFile As FileInfo) As IWithPassword(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPfxFromFile : System.IO.FileInfo -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword&lt;'ParentT&gt;" Usage="iWithData.WithPfxFromFile pfxFile" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IWithPassword&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxFile" Type="System.IO.FileInfo" />
      </Parameters>
      <Docs>
        <param name="pfxFile">PFX 形式のファイルです。</param>
        <summary>
            秘密キーの内容を取得する PFX (PKCS #12) ファイルを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
        <throws>Java.io.IOException により指定されたファイルに関する問題がある場合。</throws>
      </Docs>
    </Member>
  </Members>
</Type>